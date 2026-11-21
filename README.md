# tech









# bom

# **Smart Necklace V1 — BOM**
**1. Microcontroller — XIAO ESP32-C3**

**Approx. PKR 4,850**

- Quantity: 1
- USB-C programming
- Wi-Fi and Bluetooth LE
- Runs our display and stopwatch firmware

[See Pakistani listing](https://www.daraz.pk/products/esp32-c3-wifi-i1953921911.html?utm_source=chatgpt.com) · [Official Seeed product](https://www.seeedstudio.com/Seeed-Studio-XIAO-ESP32C3-3PCS-p-5920.html?utm_source=chatgpt.com)

**2. OLED — 0.96-inch SSD1306 I²C**

**PKR 480**

- Quantity: 1
- Resolution: 128 × 64 pixels
- Interface: I²C
- Pins: VCC, GND, SCL, SDA
- Controller: SSD1306

**3. Tactile push buttons — 6 × 6 × 5 mm**

**PKR 15 each · PKR 30 total**

- Quantity: 2
- Type: Momentary, normally open
- Mounting: Through-hole
- Button 1: MODE
- Button 2: ACTION

[Example Pakistani listing](https://www.robochacha.pk/best-sellers/?utm_source=chatgpt.com)

These are small PCB-mounted buttons. The four legs form two internally connected pairs.&#x20;

[image](https://www.google.com/s2/favicons?domain=https://www.robochacha.pk\&sz=32)

Robochacha



## **2. Connectors and mounting components**

These are important because our custom PCB needs to physically connect to the XIAO and OLED.

[Addicore Black Female Header 1x40 Pins 0.1" (2.54mm) Spacing](https://images.openai.com/static-rsc-4/gp0CCFfluQrfPHXFRCAsaOcj6a4vrpES5Bcavf8oepcGaVgVpgu3f1q1U4JZFdTODNGKbb0ZEkqk4VHbxk8NOjHozyXvxWub48v3LzVjWnPMBtnLbarm01f_e2s6GzZaF-O283RtIphdXr3vvRC8zsYuj95WCBg7AZUdga5tZOA?purpose=inline)

**4. Female header strip — 2.54 mm pitch**

**Approx. PKR 50**

- Quantity: 1 strip
- Cut into the required sections.
- Used for removable connections to the XIAO and OLED, provided their pin arrangements match.

[Example listing](https://digilog.pk/collections/buttons-switches-headers?utm_source=chatgpt.com)&#x20;

[image](https://www.google.com/s2/favicons?domain=https://digilog.pk\&sz=32)

digilog.pk



[1x40 Pin 2.54mm Pitch Male Berg Strip - Break | Robodium](https://images.openai.com/static-rsc-4/lzSvtVai9IO33O_bm5Ypvvgx67muGHDel58PrxOLnic-1s6lgclYQHrMqo2nYTOSktAss70Y6iTt2hZAtxmTYffPXFKwdARtAjhs1gKaMkko9dzx0yit7McF-UEHErNG52kKamrIyjlU3whbTH0GC8aihw5_aPmZlaE90N_XJ1E?purpose=inline)

**5. Male header strip — 2.54 mm pitch**

**Approx. PKR 30**

- Quantity: 1 strip
- Used to make compatible modules plug into the female headers.

[Example listing](https://digilog.pk/collections/buttons-switches-headers?utm_source=chatgpt.com)&#x20;

[image](https://www.google.com/s2/favicons?domain=https://digilog.pk\&sz=32)

digilog.pk



**Important:** We need to decide whether the XIAO will be removable or soldered directly to the PCB. The header arrangement above is a proposed removable setup, not a confirmed footprint yet. We must match the exact XIAO version and its pin spacing before assigning footprints.

## **3. PCB and manufacturing**

| Item                   | Quantity  | Estimated cost               |
| ---------------------- | --------- | ---------------------------- |
| Custom two-layer PCB   | 1–3       | Not quoted yet               |
| PCB assembly           | 1         | Depends on assembly method   |
| OLED mounting hardware | As needed | Not quoted                   |
| Enclosure              | 1         | Design and fabrication later |

We'll design the PCB ourselves in KiCad, then obtain a manufacturing quote once the dimensions and Gerber files are ready.

## **4. Total estimated component cost**

Estimated electronics subtotal

# **PKR 5,440**

| Component           | Price     |
| ------------------- | --------- |
| XIAO ESP32-C3       | 4,850     |
| OLED                | 480       |
| 2 buttons           | 30        |
| Female header strip | 50        |
| Male header strip   | 30        |
| **Total**           | **5,440** |
