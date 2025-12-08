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
-------
https://www.aliexpress.com/item/1005006862681936.html
<img width="164" height="222" alt="image" src="https://github.com/user-attachments/assets/cc999876-801e-4294-accd-adeab7e2bc6c" />
https://www.aliexpress.com/item/1005006027343580.html
<img width="403" height="163" alt="image" src="https://github.com/user-attachments/assets/ed812228-93c5-492d-b8a6-510a57a193f3" /> 

bekötés tx-tx, rx-rx!!! Ezen a boardon fel van cserélve a felirat:
-----------------------
<img width="246" height="612" alt="image" src="https://github.com/user-attachments/assets/4ccd3a15-2625-4063-a9d9-53bd6092b4eb" /> <img width="587" height="463" alt="image" src="https://github.com/user-attachments/assets/e0b2cb1d-1822-40b6-99d3-0b6c6f14de0d" />




Dashboard minta:
----------------
<img width="346" height="776" alt="image" src="https://github.com/user-attachments/assets/ad357bdc-4c05-4951-a37d-47df61a41a0e" />


összes adat:
------------
<img width="335" height="719" alt="image" src="https://github.com/user-attachments/assets/7134d8b6-6525-4c76-b50d-46b9ab8ed433" /> <img width="342" height="727" alt="image" src="https://github.com/user-attachments/assets/baa88f0e-e3bf-4b04-b7dc-789c906a6c47" /> <img width="339" height="723" alt="image" src="https://github.com/user-attachments/assets/8b06d38d-a771-4ce6-a564-c94d9e1dbef5" />








