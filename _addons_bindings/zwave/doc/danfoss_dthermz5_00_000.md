---
layout: documentation
title: DTHERMZ5 - ZWave
---

{% include base.html %}

# DTHERMZ5 Z-Wave room sensor

This describes the Z-Wave device *DTHERMZ5*, manufactured by *Danfoss* with the thing type UID of ```danfoss_dthermz5_00_000```. 

Z-Wave room sensor


## Channels
The following table summarises the channels available for the DTHERMZ5 Z-Wave room sensor.

| Channel | Channel Id | Channel Type UID | Category | Item Type |
|---------|------------|------------------|----------|-----------|
| Sensor (temperature) | sensor_temperature | sensor_temperature | Temperature | Number |
| Setpoint (cooling) | thermostat_setpoint_cooling | thermostat_setpoint | Temperature | Number |
| Setpoint (heating) | thermostat_setpoint_heating | thermostat_setpoint | Temperature | Number |
| Scene Number | scene_number | scene_number |  | Number |
|  | battery-level | system.battery-level |  |  |


### Sensor (temperature)

#### Scale

Select the scale for temperature readings


| Property         | Value    |
|------------------|----------|
| Configuration ID | config_scale |
| Data Type        | TEXT || Default Value | 0 |
| Options | Celsius (0) |
|  | Fahrenheit (1) |


### Setpoint (cooling)

#### Scale

Select the scale to use for setpoints.


| Property         | Value    |
|------------------|----------|
| Configuration ID | config_scale |
| Data Type        | TEXT || Default Value | 0 |
| Options | Celsius (0) |
|  | Fahrenheit (1) |


### Setpoint (heating)

#### Scale

Select the scale to use for setpoints.


| Property         | Value    |
|------------------|----------|
| Configuration ID | config_scale |
| Data Type        | TEXT || Default Value | 0 |
| Options | Celsius (0) |
|  | Fahrenheit (1) |


### Device Configuration
The following table provides a summary of the configuration parameters available in the DTHERMZ5 Z-Wave room sensor.
Detailed information on each parameter can be found below.

| Parameter   | Description |
|-------------|-------------|
| 1: Temperature Report threshold | Range is from 0.1 to 10°C 1=0.1°C 100=10°C |
| 2: Set-point display resolution | range from 0.1 to 10°C 1=0.1°C 100=10°C |
| 3: Min Set-point and override limit | from min 0°C to max setpoint override limit 0=0°C 40=40°C |
| 4: Max Set-point and override limit | from min setpoint override limit to max 40°C 0=0°C 40=40°C |
| 5: LED Flash period | 0 to 65535 seconds |
| 6: Set-point control function | 0=Disabled 1=Enabled |
| 7: Temporarily override scheduler | 0=Disabled 1=Enabled |
| 8: Set-point type in Thermostat_Setpoint_Reports | 1=Heating 2=Cooling 10=Auto Changeover |
| 9: LED on time | 1=100ms 5=500ms |
| 10: Number of LED flashes (duration) | 0 to 255 |
| 11: LED color | 1=Green 2=Red |


#### 1: Temperature Report threshold

Range is from 0.1 to 10°C 1=0.1°C 100=10°C  


##### Overview 

Default value 5 = 0.5 °C


| Property         | Value    |
|------------------|----------|
| Configuration ID | config_1_2 |
| Data Type        | INTEGER |
| Range | 1 to 100 |
| Default Value | 5 |


#### 2: Set-point display resolution

range from 0.1 to 10°C 1=0.1°C 100=10°C


| Property         | Value    |
|------------------|----------|
| Configuration ID | config_2_2 |
| Data Type        | INTEGER |
| Range | 1 to 100 |
| Default Value | 5 |


#### 3: Min Set-point and override limit

from min 0°C to max setpoint override limit 0=0°C 40=40°C


| Property         | Value    |
|------------------|----------|
| Configuration ID | config_3_2 |
| Data Type        | INTEGER |
| Range | 0 to 40 |
| Default Value | 12 |


#### 4: Max Set-point and override limit

from min setpoint override limit to max 40°C 0=0°C 40=40°C


| Property         | Value    |
|------------------|----------|
| Configuration ID | config_4_2 |
| Data Type        | INTEGER |
| Range | 0 to 40 |
| Default Value | 28 |


#### 5: LED Flash period

0 to 65535 seconds


| Property         | Value    |
|------------------|----------|
| Configuration ID | config_5_4 |
| Data Type        | INTEGER |
| Range | 0 to 65535 |
| Default Value | 1 |


#### 6: Set-point control function

0=Disabled 1=Enabled


| Property         | Value    |
|------------------|----------|
| Configuration ID | config_6_1 |
| Data Type        | INTEGER || Default Value | 1 |
| Options | disabled (0) |
|  | enabled (1) |


#### 7: Temporarily override scheduler

0=Disabled 1=Enabled


| Property         | Value    |
|------------------|----------|
| Configuration ID | config_7_1 |
| Data Type        | INTEGER || Default Value | 1 |
| Options | disabled (0) |
|  | enabled (1) |


#### 8: Set-point type in Thermostat_Setpoint_Reports

1=Heating 2=Cooling 10=Auto Changeover


| Property         | Value    |
|------------------|----------|
| Configuration ID | config_8_1 |
| Data Type        | INTEGER || Default Value | 1 |
| Options | Heating (1) |
|  | Cooling (2) |
|  | Auto-Changeover (10) |


#### 9: LED on time

1=100ms 5=500ms


| Property         | Value    |
|------------------|----------|
| Configuration ID | config_9_2 |
| Data Type        | INTEGER |
| Range | 1 to 5 |
| Default Value | 1 |


#### 10: Number of LED flashes (duration)

0 to 255


| Property         | Value    |
|------------------|----------|
| Configuration ID | config_10_1 |
| Data Type        | INTEGER |
| Range | 0 to 255 |
| Default Value | 5 |


#### 11: LED color

1=Green 2=Red


| Property         | Value    |
|------------------|----------|
| Configuration ID | config_11_1 |
| Data Type        | INTEGER || Default Value | 1 |
| Options | Green (1) |
|  | Red (2) |


---

Did you spot an error in the above definition or want to improve the content?
You can edit the database [here](http://www.cd-jackson.com/index.php/zwave/zwave-device-database/zwave-device-list/devicesummary/501).
