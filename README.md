# ESPHome-Voice-Assistant-Cheechka-

Eredeti projekt: https://www.facebook.com/groups/895509620623859/?multi_permalinks=2534590173382454

Demo video: https://youtu.be/QEmGbse2EoY

1) ESP32 Devkit - Vágd le a lábait, hogy beférjen a hangszóró mögé, valamint 5V szűrt táp (miniPC USB) kell neki, különben csak recseg és nem bootol. 
   https://www.emag.ro/placa-dezvoltare-esp32-devkit-v1-ai669/pd/DXV9FDMBM/
3) Mikrofon INMP441 = https://www.emag.ro/microfon-digital-1-4-ma-microphone-inmp441-mod/pd/DCR798MBM/
4) 1db WS2812 RGB led = https://www.emag.ro/inel-led-1bit-ws2812-rgb-ai1152/pd/D21CKJMBM/
5) Erőssitő (DAC) MAX98357 = https://ardushop.ro/ro/home/2666-max98357-i2s-3w-class-d-amplifier-module.html
6) Hangszóró Amazon Basics (emag-on kapható kb. 10EUR) = https://www.emag.ro/boxe-pc-laptop-amazonbasics-cu-sunet-dinamic-si-iluminare-led-usb-c-a-3-5mm-jack-5-w-negru-v620black/pd/DTHBN2YBM/
7) 1 led-es ESPHOme Yaml config = csatolva
8) Custom intents (csatolva): https://github.com/lajoshanko/HA-custom-intents
9) Rajz (csatolva): https://github.com/cyberelectronics/ESPHome-Voice-Assistant-Cheechka-/blob/main/Pictures/sch.jpg

Egyébb linkek:
> Bővebben az egészről (tekerj bele; Whisper felejtős, csak Google STT vagy Nabu Casa jöhet szóba): https://www.youtube.com/live/YzgYYkOrnhQ?si=le9z8jAjHA8LGLPM . 
   Még egy kis segitség: https://youtu.be/zhlIaBG3Ldo?si=DnuwGsu_6ooKxfZT

> Amennyiben az ingyenes Google STT szeretnéd használni, tudnod kell, hogy havonta 60 perc használat van ingyen (kérdezz-felelek), utána fizetős.
 API key készitése: https://www.home-assistant.io/integrations/google_cloud . 
Google Cloud STT integrálása: https://github.com/chatziko/ha-google-cloud-stt

> Egyébb magyar utasitások: https://github.com/home-assistant/intents/tree/main/sentences/hu

> Saját wakeword, készitése-felhasználása: https://www.home-assistant.io/voice_control/create_wake_word/

> ESPHome alapok: https://esphome.io/guides/getting_started_hassio 

 
