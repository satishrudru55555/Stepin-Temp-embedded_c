# **Test Plans**

| **Test ID** | **Description** | **Input** | **Output** | **Status** |
| --- | --- | --- | --- | --- |
| TID\_01 | Is person seated | push button1=1 | push button1=1 | PASS |
| TID\_02 | Is personseated | Push button1=0 | Push button1=0 | PASS |
| TIB\_03 | Is heater ON | Push button2=1 | Push button2=1 | PASS |
| TID\_04 | Is heater OFF | push button2=0 | push button2=0 | PASS |
| TID\_05 | Temperature Request | Temp=0 | heater=Off | PASS |
| TID\_06 | Temperature Request | Temp=20 | heater=20 degree generation | PASS |
| TID\_07 | Temperature Request | Temp=25 | heater=25 degree generation | PASS |
| TID\_08 | Temperature Request | Temp=29 | heater=29 degree generation | PASS |
| TID\_09 | Temperature Request | Temp=33 | heater=33 degree generation | PASS |
| TID\_10 | LED ON | Button=1 &amp;&amp; Heater=1 | LED=1 | PASS |
| TID\_11 | LED OFF | Button=0 &amp;&amp; Heater=0 | LED=0 | PASS |
| TID\_12 | Display | Temperature :20 deg Cel | Temperature :20 deg Cel | PASS |
