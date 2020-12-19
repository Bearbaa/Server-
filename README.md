# Server-i'm running a DayZ server and it keeps crashing. This is the exact coding of the crash log. I'm looking for anyone that can possibly tell me what the issue is. Thank you in advance. 
LSN-D3053, 19.12 2020 00:33:34
NULL pointer to instance
Class:      'Hologram'
Function: 'EvaluateCollision'
Stack trace:
OP_BaseItems/scripts/4_World/moddedclasses\hologram.c:19
ModularVestSystem/scripts/4_World/armorrack_hologram.c:31
BaseBuildingPlus/scripts/4_World/overrides\hologram.c:142
scripts/4_World/classes\useractionscomponent\actions\continuous\actiondeployobject.c:253
server_logs/scripts/4_World/classes\useractioncomponent\actions\continuous\actiondeployobject.c:7
scripts/4_World/classes\useractionscomponent\actions\actioncontinuousbase.c:203
scripts/4_World/classes\useractionscomponent\actioncomponents\cacontinuousbase.c:12
scripts/4_World/classes\useractionscomponent\actioncomponents\cacontinuoustime.c:53
scripts/4_World/classes\useractionscomponent\animatedactionbase.c:60
scripts/4_World/classes\useractionscomponent\animatedactionbase.c:347
scripts/4_World/classes\useractionscomponent\actions\actioncontinuousbase.c:28 
