# ST\_attrIntMin {#reference_yqh_kyp_3gb .reference}

This function returns the minimum value of an integer-type attribute field.

## Syntax {#section_og1_4hn_qfb .section}

```
int8 ST_attrIntMin(trajectory traj, cstring attr_field_name);
```

## Parameters {#section_cxv_qhn_qfb .section}

|Parameter|Description|
|---------|-----------|
|traj|The trajectory object.|
|attr\_field\_name|The name of the attribute field.|

## Examples {#section_lmw_qhn_qfb .section}

```
select st_attrIntMin(ST_makeTrajectory('STPOINT'::leaftype, 'LINESTRING(-179.48077 51.72814,-179.46731 51.74634,-179.46502 51.74934,-179.46183 51.75378,-179.45943 51.75736,-179.45560 51.76273,-179.44845 51.77186,-179.43419 51.78977,-179.41259 51.81643,-179.41001 51.81941,-179.40751 51.82223,-179.40497 51.82505,-179.40242 51.82796,-179.39981 51.83095,-179.39734 51.83398,-179.39499 51.83709)'::geometry, ARRAY['2017-01-15 09:06:39'::timestamp,'2017-01-15 09:14:48','2017-01-15 09:13:39','2017-01-15 09:16:28','2017-01-15 09:19:48','2017-01-15 09:17:48','2017-01-15 09:23:19','2017-01-15 09:34:40','2017-01-15 09:30:28','2017-01-15 09:36:59','2017-01-15 09:38:09','2017-01-15 09:39:18','2017-01-15 09:40:40','2017-01-15 09:47:38','2017-01-15 21:18:30','2017-01-15 09:48:49'], '{"leafcount": 16, "attributes": {"heading": {"type": "integer", "length": 4, "nullable": false,"value":[0,1,2,3,4,5,6,7,8,9,10,11,12,13,14,15]}}}'), 'heading'); 
 st_attrintmin 
---------------
            0
```

