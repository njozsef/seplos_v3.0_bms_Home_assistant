# seplos_v3.0_bms_Home_assistant
Seplos V3.0 BMS - home assistant interface (fork from https://github.com/syssi/esphome-seplos-bms )



hardvare:
--------
ESP32 S3 zero board (vagy más esp32)
ttl - rs485 konverter board
1/2 utp patch kábel

software:
--------
Home Assistant
  - HACS
    -ESPHome Builder
    -button-card (dashboard extension)
    -bar-card
    -apexchart-card

A HACS dashboard extension nélkül is működik, de akkor nem működik a megjelenítés csak az adatok jönnek.

huzalozás:
---------          _________________________________________                                      ____________________
      |--3.3V-----| 3.3V                                    |                                    |
esp32 |--TX-------|  TX!        RS485 konverter           A+|------UTP narancs-------------------|   BMS 485-1 csatlakozó
      |--RX-------|  RX!                                  B-|------UTP narancs-fehér-------------|       (középső)
      |----GND----|  GND                                    |                                    |
                  ------------------------------------------                                      --------------------

A DIP kapcsoló 1-es kapcsolóját fel (on)


