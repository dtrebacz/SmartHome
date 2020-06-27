# SmartHome
######################################################################################################
QS_Script6.bin - kompilacja tasmoty w języku polskim z obsługą skruptów
######################################################################################################
qs_srypt_DTpoprawiony.txt - skrypt dla przekaźnika dopuszkowego TUYA QS-WIFI-S04-2C
ustawienia dla tasmoty:

Pinouts are :- generic(18)
GPIO2 - Button1 (17) 
GPIO4 - Buzzer (160)
GPIO12 - Counter2 (43)
GPIO13 - Counter1 (42)
GPIO14 - Relay1 (21)
GPIO15 - Relay2 (22)

Skrypt obsluguje przełączenie ze standartowego wyłącznika świecznikowego lub schodowego.
Mapuje stan przekaźników po przełączeniu z MQTT, także załączanie/wyłaczanie działa z obu miejsc
można załączyż poprzez MQTT i wyłaczyć wyłącznikie i odwrotnie
dodatkowo wyłączenie przekażników po zaniku zasilania lub restarcie

######################################################################################################
