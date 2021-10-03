# PLC_traffic_light_rtc

Cf. https://www.plctalk.net/qanda/showthread.php?t=130748

Minimal two-way traffic lights, with overlap of reds

Rung 0000 controls daytime vs. nighttime operations, with manual overrides that switch only at the top of a minute.

Daytime operations:  green-yellow-red sequence
Nighttime operations:  yellow flashing for one path; red on solid the other path.

![](https://github.com/drbitboy/PLC_traffic_light_rtc/raw/master/traffic_light_rtc.png)
