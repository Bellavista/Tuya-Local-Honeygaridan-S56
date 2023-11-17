# Tuya-Local-Honeygaridan-S56
Tuya-local configuration For Pet Feeder Honeygaridan-S56
https://www.honeyguardian.com/collections/feeder/products/honeyguardian-6l-smart-cat-feeder?variant=46640566272293

![image](https://github.com/Bellavista/Tuya-Local-Honeygaridan-S56/assets/46230198/07d5bef5-2efd-4c8e-a9a7-62d00d5f7fdc)

Home assistant configuration

![image](https://github.com/Bellavista/Tuya-Local-Honeygaridan-S56/assets/46230198/969e252e-068d-402c-a43c-7019d74c8bc9)
![image](https://github.com/Bellavista/Tuya-Local-Honeygaridan-S56/assets/46230198/10b7822a-fada-4f97-b1d8-4f769afd62b2)

Entity List
HONEYGUARIDAN S56 App Style
select.honeyguaridan_s56_app_style
App Style color 
( "1"-"Dark", "2"-"White", "3"-"Ciano", "4"-"Violet","5"-"Ciano-Violet")

![image](https://github.com/Bellavista/Tuya-Local-Honeygaridan-S56/assets/46230198/2a1092ef-46a5-4ce2-ac14-8e135d27fabd)


HONEYGUARIDAN S56 Battery Level
sensor.honeyguaridan_s56_battery_level
Battery level ("empty"-"EMPTY !!!", "low"-"LOW !", "high"-"HIGH", "full"-"FULL")

![image](https://github.com/Bellavista/Tuya-Local-Honeygaridan-S56/assets/46230198/11e5cfd2-f2bf-42e8-a854-496ee6240807)


HONEYGUARIDAN S56 Error code 
sensor.honeyguaridan_s56_error_code
Error code 
(This model don't have a sensor the value is unknow, HoneyGuaridan write ERR1: Corrente motore anomala
ERR3: Rilevamento anomalo della griglia a infrarossi durante la rotazione.
ERR4:ERR1+ERR3)
( 0 - "OK", "food_run_out" - "food_run_out", "ERR1" - "ERR1 - TO DEFINE", "ERR3" - "ERR3 - TO DEFINE", "ERR5" - "ERR5 - TO DEFINE"

![image](https://github.com/Bellavista/Tuya-Local-Honeygaridan-S56/assets/46230198/48b7225e-3ed6-49c7-b61b-3ec09ff4880d)


HONEYGUARIDAN S56 Hour 12/24
switch.honeyguaridan_s56_hour_12_24
Hours format ( ON - 00:00 - 23:59, OFF 00:00 12:00 pm/am)
![image](https://github.com/Bellavista/Tuya-Local-Honeygaridan-S56/assets/46230198/fef411cf-502e-4ef4-8884-aec53d21cb0d)


HONEYGUARIDAN S56 Manual Feeding
number.honeyguaridan_s56_manual_feeding
Manual feeding portion (if modified the device distributes the chosen portion number )

![image](https://github.com/Bellavista/Tuya-Local-Honeygaridan-S56/assets/46230198/4d860faa-d1a6-4020-a868-a6ec965f9390)


HONEYGUARIDAN S56 Meal Log
number.honeyguaridan_s56_meal_log
Meal log ( number of portions distributed in the last programming)

![image](https://github.com/Bellavista/Tuya-Local-Honeygaridan-S56/assets/46230198/f698234c-d654-46d4-99e2-2913343be9ad)


- HONEYGUARIDAN S56 Planning
sensor.honeyguaridan_s56_planning
Base64 CODE:
exsample "value": "DAABAQweAgENAAQBDR4DAQ4ABAEOHgYB"
exsample :       hour     minute   portion   planned
exsample Plan 1: 00001100 00000000 00000001 00000001 12:00 1 meal portion yes planned
exsample Plan 2: 00001100 00011110 00000010 00000001 12:30 2 meal portion yes planned
exsample Plan 3: 00001101 00000000 00000011 00000000 13:00 3 meal portion no planned
exsample Plan 4: 00001101 00011110 00000100 00000001 13:30 4 meal portion yes planned
exsample Plan 5: 00001110 00000000 00000101 00000001 14:00 5 meal portion yes planned
exsample Plan 6: 00001110 00011110 00000110 00000001 14:30 6 meal portion yes planned

![image](https://github.com/Bellavista/Tuya-Local-Honeygaridan-S56/assets/46230198/f82b9907-9bc9-4a6c-8863-9cd25ef70b1d)

HONEYGUARIDAN S56 Slow Feeding
switch.honeyguaridan_s56_slow_feeding
Slow Feed (motor pause during rotation)
![image](https://github.com/Bellavista/Tuya-Local-Honeygaridan-S56/assets/46230198/64a3ceb5-4d40-47cd-86ac-1c117880966b)


HONEYGUARIDAN S56 Vocal Message
number.honeyguaridan_s56_vocal_message
Vocal message (number of voice message repetitions before food distribution)

![image](https://github.com/Bellavista/Tuya-Local-Honeygaridan-S56/assets/46230198/4bf648e4-7db3-47fc-abbc-9c30f9e25342)

