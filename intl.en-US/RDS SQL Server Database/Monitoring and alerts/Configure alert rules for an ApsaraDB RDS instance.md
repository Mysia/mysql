# Configure alert rules for an ApsaraDB RDS instance

This topic describes how to monitor an apsaradb for RDS instance. This function provides the ability to notify you when an instance exception is detected. In addition, the system will notify you when the instance is locked due to insufficient disk capacity.

## Create alert rules

1.  Log on to the [ApsaraDB for RDS console](https://rds.console.aliyun.com/).

2.  In the left-side navigation pane, click **Instances**. In the top navigation bar, select the region where your RDS instance resides.

    ![Select a region](https://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/en-US/8651559951/p36543.png)

3.  Find your RDS instance and click its ID.

4.  In the left-side navigation pane, click **Monitoring and Alerts**.

5.  Click the **Alerts** tab.

6.  Click **Set Alert Rule** to go to the Cloud Monitor console.

    ![Set Alert Rule](https://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/en-US/2350359951/p95893.png)

7.  Create an alert contact group. For more information, see [Create an alert contact or alert group](/intl.en-US/Alarm service/Alert contacts/Create an alert contact or alert group.md).

8.  Create alert rules. For more information, see [Create a threshold-triggered alert rule](/intl.en-US/Alarm service/Alarm rules/Create a threshold-triggered alert rule.md).

    **Note:** You can also configure Cloud Monitor to automatically monitor resources based on tags. For more information, see [Monitor resources based on tags](/intl.en-US/Best Practices/Monitor resources based on tags.md).


## Manage alert rules

1.  Log on to the [ApsaraDB for RDS console](https://rds.console.aliyun.com/).

2.  In the left-side navigation pane, click **Instances**. In the top navigation bar, select the region where your RDS instance resides.

    ![Select a region](https://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/en-US/8651559951/p36543.png)

3.  Find your RDS instance and click its ID.

4.  In the left-side navigation pane, click **Monitoring and Alerts**.

5.  Click the **Alerts** tab.

6.  Click **Set Alert Rule** to go to the Cloud Monitor console.

    ![Set Alert Rule](https://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/en-US/2350359951/p95893.png)

7.  On the **Alarm Rules** tab, find the target alert rule and in the Actions column select one of the following operations:

    -   View: View details about the alert rule.
    -   Alarm Logs: View the alerts that were triggered by the alert rule over a specific period of time.
    -   Modify: Modify the alert rule. For more information about the parameters, see [Alarm rule parameters](/intl.en-US/Alarm service/Alarm rules/Alarm rule parameters.md).
    -   Disable: Disable the alert rule. After you disable the alert rule, no alerts will be triggered even if the metric meets the conditions specified in the alert rule.
    -   Delete: Delete the alert rule. After you delete an alert rule, the alert rule cannot be restored. You can only re-create the alert rule if necessary.

