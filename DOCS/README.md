# ODM-01

## Zine

## What It Is & Why I Made It

It is a decorative/ badge-like PCB shaped like the Attack On Titan 'Wings of Freedom' emblem. I honestly wanted to make something anime related, that was fun but also a beginner friendly project. So I made this PCB with my previous knowledge. First I wanted to make the whole PCB like the Attack On Titan badge but that didn't really work out so I opted for something that I had a bit more knowledge of. So, I decided to really embody the badge in the silkscreen.

This board consists of 14 LEDs around the perimeter which I kept for a glowing effect. It is portable as I have added a coin cell battery holder for convinience and to be able to wear it like an actual badge. It has resistors, IC, and also a capacitor for driving the LED. Also consists of a test point to probe voltage during testing and debugging.

## How To Use It

1. Insert a CR2032 coin cell battery into the battery holder at the base, make sure the polarity matches the markings on the board.
2. Once the battery is kept, the circuit powers on automatically and the LEDs will light up.
3. The light sensor will automtically adjust the LEDs based on surrounding brightness.
4. Attach the badge to anything!
5. If the LEDs don't light up, use a multimeter on the test point to check the voltage and identify any soldering issue.

## BOM

# Bill of Materials — ODM-01

| Item                          | Description                  | Qty | Unit Price | Total Price | URL                                                                        |
| ----------------------------- | ---------------------------- | --- | ---------- | ----------- | -------------------------------------------------------------------------- |
| 5mm LED (Red)                 | Perimeter LEDs               | 14  | $0.10      | $1.40       | https://www.aliexpress.com/item/1005006225914769.html                      |
| Resistor Kit (through-hole)   | Current-limiting resistors   | 5   | $0.05      | $0.25       | https://www.aliexpress.com/item/1005003271232838.html                      |
| GL5528 LDR                    | Light sensor (photoresistor) | 1   | $0.25      | $0.25       | https://www.aliexpress.com/item/1005002388823502.html                      |
| 100uF Electrolytic Capacitor  | Power smoothing capacitor    | 1   | $0.15      | $0.15       | https://www.aliexpress.com/item/1005003291510890.html                      |
| 2N3904 NPN Transistor         | LED switching transistor     | 1   | $0.10      | $0.10       | https://www.digikey.com/en/products/detail/onsemi/2N3904BU/1413            |
| NE555 Timer IC                | LED driver IC                | 1   | $0.35      | $0.35       | https://www.digikey.com/en/products/detail/texas-instruments/NE555P/277594 |
| CR2032 Coin Cell Holder       | PCB-mount battery holder     | 1   | $0.89      | $0.89       | https://www.adafruit.com/product/4856                                      |
| CR2032 Coin Cell Battery      | 3V power source              | 1   | $0.99      | $0.99       | https://www.amazon.com/dp/B071D2XTW4                                       |
| **TOTAL**                     |                              |     |            | **$4.38**   |                                                                            |

> Prices are estimates.

# JLC PCB

<img width="1803" height="591" alt="image" src="https://github.com/user-attachments/assets/ab558483-02e9-483c-b2ae-f6d9db903b35" />

## Schematic
<img width="689" height="449" alt="image" src="https://github.com/user-attachments/assets/805f20a2-0c16-456b-8402-259e6af80429" />

## PCB
<img width="429" height="550" alt="image" src="https://github.com/user-attachments/assets/844e13f3-1566-499b-995b-a7e1b76bfb03" />

## 3d View
<img width="619" height="720" alt="image" src="https://github.com/user-attachments/assets/2c99ff1b-5368-411a-b48d-5af93e04eeec" />
