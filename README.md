# seplos_v3.0_bms_Home_assistant
Seplos V3.0 BMS - home assistant interfész (forkolva https://github.com/syssi/esphome-seplos-bms )

Lovelace dashboard yaml (forkolva https://github.com/klatremis/esphome-for-bms )



hardver:
--------
ESP32 S3 zero board (vagy más esp32)
ttl - rs485 konverter board
1/2 utp patch kábel

szoftver:
--------
Home Assistant
  - HACS
    -ESPHome Builder
    -button-card (dashboard extension)
    -bar-card
    -apexchart-card

A HACS dashboard extension nélkül is működik, de akkor nem megy a klatremis által írt megjelenítés csak az adatok jönnek.

<img width="849" height="169" alt="image" src="https://github.com/user-attachments/assets/62929718-31c4-4333-8f71-51d26158103c" />


A DIP kapcsoló 1-es kapcsolóját fel (on)


boardok:
https://www.aliexpress.com/item/1005006862681936.html
<img width="164" height="222" alt="image" src="https://github.com/user-attachments/assets/cc999876-801e-4294-accd-adeab7e2bc6c" />
https://www.aliexpress.com/item/1005006027343580.html
<img width="403" height="163" alt="image" src="https://github.com/user-attachments/assets/ed812228-93c5-492d-b8a6-510a57a193f3" />



Dashboard sample:
----------------
https://github.com/klatremis/esphome-for-bms/blob/main/lovelace_dashboard.png



