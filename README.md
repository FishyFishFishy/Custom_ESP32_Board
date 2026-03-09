# Custom_ESP32_Board
Making a custom ESP32 Board for generic use

After making my devboard with an RP2040, I wanted to have something with an ESP32 MCU. I want to use this for general purpose projects that need additional wifi/bluetooth support. In particular, I want to make some automated window blinds and a one handed soldering tool, so I am using this as a stepping stone to learn this pcb design.

This board has a USB Type-C port to flash and power it.

Schematic:
<img width="1437" height="900" alt="Screenshot 2026-03-09 at 4 56 26 PM" src="https://github.com/user-attachments/assets/00bbfe99-ea33-49c9-9727-7f61a52fd27d" />

PCB Layout:
<img width="1440" height="900" alt="Screenshot 2026-03-09 at 4 56 17 PM" src="https://github.com/user-attachments/assets/48a87222-c63e-47ac-84f8-6b12621b8ebd" />

3D Model:
<img width="1275" height="701" alt="Screenshot 2026-03-09 at 4 56 44 PM" src="https://github.com/user-attachments/assets/07c55b5f-9a62-452a-98fb-e75c6fdca2cd" />

BOM:
| Item Description | Supplier | Supplier Part # | Mfr Part # | Qty | Unit Price | Extended Price |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| CAP CER 10UF 25V X5R 0805 | DigiKey | 1276-6454-1-ND | CL21A106KAYNNNG | 35 | $0.08900 | $3.12 |
| CAP CER 1UF 16V X5R 0603 | DigiKey | 1276-1034-1-ND | CL10A105KO8NNNC | 10 | $0.03100 | $0.31 |
| RES 10K OHM 1% 1/8W 0603 | DigiKey | RNCP0603FTD10K0CT-ND | RNCP0603FTD10K0 | 40 | $0.01080 | $0.43 |
| CAP CER 0.1UF 50V X7R 0603 | DigiKey | 1276-CL10B104KB8NNNLCT-ND | CL10B104KB8NNNL | 50 | $0.01800 | $0.90 |
| IC REG LINEAR 3.3V 1A SOT-223-3L | DigiKey | 4518-AMS1117-3.3CT-ND | AMS1117-3.3 | 10 | $0.20000 | $2.00 |
| CAP CER 22PF 50V C0G/NP0 0603 | DigiKey | 399-C0603C220J5GACTUCT-ND | C0603C220J5GACTU | 10 | $0.06900 | $0.69 |
| SWITCH TACTILE SPST-NO 0.05A 16V | DigiKey | CKN10504CT-ND | PTS810SJG250SMTR LFS | 20 | $0.50700 | $10.14 |
| LED BLUE CLEAR CHIP SMD | DigiKey | 160-1646-1-ND | LTST-C190TBKT | 10 | $0.09400 | $0.94 |
| RF TXRX MOD BT WIFIU.FL SMD | DigiKey | 1965-ESP32-S3-WROOM-1U-N16R8CT-ND | ESP32-S3-WROOM-1U-N16R8 | 5 | $6.56000 | $32.80 |
| RF TXRX MOD BT WIFI PCB TH SMD | DigiKey | 5407-ESP32-C3-MINI-1-H4CT-ND | ESP32-C3-MINI-1-H4 | 5 | $3.28000 | $16.40 |
| 1N5819HW-7-F (Diode 40V 1A SOD-123) | LCSC | C82544 | 1N5819HW-7-F | 20 | $0.0295 | $0.59 |
| SK6812 LED Addressable SMD-4P | LCSC | C5378720 | SK6812 | 10 | $0.0870 | $0.87 |
| 5.1kΩ ±0.1% 125mW 0805 Ceramic Resistor | LCSC | C2912598 | HoAR0805-1/8W-5.1KR-0.1% | 20 | $0.0776 | $1.55 |
| 200Ω ±0.1% 130mW 0805 Thin Film Resistor| LCSC | C2849095 | PTFR0805B200RP9 | 10 | $0.0733 | $0.73 |
| USB-C Receptacle 16-Pin Right Angle | LCSC | C2765186 | TYPE-C 16PIN 2MD(073) | 20 | $0.0615 | $1.23 |
| ESD5B5.0ST1G ESD Protection | LCSC | C93623 | ESD5B5.0ST1G | 40 | $0.0362 | $1.45 |
