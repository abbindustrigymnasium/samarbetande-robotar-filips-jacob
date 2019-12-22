# Samarbetande Robotar

**Filip Segerbergs och Jacob Engström arbete till projektet Samarbetande Robotar**

## Hårdvara

Den hårdvara vi har använt är:

- ESP8266 samt en ESP8266 motor-shield
- DC-DC step-up
- DC elmotor
- Ett kretskort designat till hallelemetntet SS49e

## Installation

För att våran mikrodator ska kunna skicka och ta i mot MQTT behöver man ett tredjepartsbiblotek, vi har valt EspMQTTClient. Klicka **[HÄR](https://github.com/plapointe6/EspMQTTClient)** för att gå till deras Github.

## Hemsida

Hemsidan används för att kunna ändra börhastigheten på bilarn, stoppa bilarna samta se på en graf båda bilarnas PWM värde och aktuela hastighet Klicka **[HÄR](http://jacob-filips.s3-website-us-east-1.amazonaws.com)** för att gå till våran hemsida.

## Arbetsfördelning

När vi har arbetet med prodjektet så har vi oftast arbetat tillsamans men Jacob arbetade mer med hemsidan och Filip.S arbetade mera med arduinokoden. Vi tycket att samanrbetet har gått bra och vi har ungefär lika många timmar lagda på prodjektet för att det skulle bli klart.

## Problem

Filip.S bil kan köra en konstant hastighet samt skicka sin data med MQTT till våran hemsida där den visas på en graf, men Jacobs bil är det något som gör att arduinokortet inte regestrerar pulserna ifrån hall-elementet. Vi har gjort en grundlig felsökning utan något resultat. Vi ska arbeta mer unter vårtetminan för att lösa problemet.
