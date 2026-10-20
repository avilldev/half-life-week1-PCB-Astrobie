# Astrobie: A close encounter in your pocket

<img width="1107" height="591" alt="image" src="https://github.com/user-attachments/assets/92e583c3-61ee-4a26-b361-74ed3de60a20" />

## What it is

Astrobie is a custom-designed PCB digital pet powered by a Seeed XIAO ESP32-C3. This project was made for the first-week PCB submission for Hackclub's [Half Life](https://halflife.hackclub.com/?ref=1941)
program. It is based on their beginner guide, [Starbie](https://github.com/SharKingStudios/Starbie/blob/main/Week%201%20Guide.md). However, I customized the project to have a different theme.
It features a UFO-themed circuit board, a 128x64 OLED screen displaying an alien sprite, an MPU6050 accelerometer, a DHT11 temperature/humidity sensor, and two push buttons.

## How it works

The pet wanders around the OLED screen.

- **Motion Control:** After pressing the menu button, the board can be tilted to select actions such as Fuel, Fly, Scan, or Dock.
- **Animations:** Each action has an animation. For example, selecting the Dock action triggers a nap cycle with floating "z" characters.
- **Sensors:** The MPU6050 detects shaking to wake the pet up. The DHT11 reads real-world room temperature and humidity to display in the stats.

# BOM
| Part | What it's for | Qty | Unit | Total | Vendor |
| --- | --- | --- | --- | --- | --- |
| [128X64 OLED I2C](https://www.alibaba.com/product-detail/0-96-Inch-OLED-Module-White_1601198774090.html?spm=a2700.prosearch.normal_offer.d_image.682967afhsdOnQ&selectedCarrierCode=SEMI_MANAGED_STANDARD%40%40STANDARD&priceId=05ce4363f14d482eb0f208be919ad1ec) | OLED Screen | 1 | $1.15 | $1.15 | [Alibaba](https://www.alibaba.com/product-detail/0-96-Inch-OLED-Module-White_1601198774090.html?spm=a2700.prosearch.normal_offer.d_image.682967afhsdOnQ&selectedCarrierCode=SEMI_MANAGED_STANDARD%40%40STANDARD&priceId=05ce4363f14d482eb0f208be919ad1ec) |
| [MPU6050](https://www.alibaba.com/product-detail/GY-521-MPU-6050-Module-Triaxial_1601115321765.html?spm=a2700.prosearch.normal_offer.d_image.127d67afBWjVm8&selectedCarrierCode=SEMI_MANAGED_STANDARD%40%40STANDARD&priceId=17b392fcdf3b4fcb89bf8703774ffdd2) | Acceleration Gyroscope Module | 1 | $1.09 | $1.09 | [Alibaba](https://www.alibaba.com/product-detail/GY-521-MPU-6050-Module-Triaxial_1601115321765.html?spm=a2700.prosearch.normal_offer.d_image.127d67afBWjVm8&selectedCarrierCode=SEMI_MANAGED_STANDARD%40%40STANDARD&priceId=17b392fcdf3b4fcb89bf8703774ffdd2) |
| [DHT11](https://www.alibaba.com/product-detail/DHT11-Digital-Temperature-and-Humidity-Sensor_1600053358031.html?spm=a2700.prosearch.normal_offer.d_image.100167afkOugAf&selectedCarrierCode=SEMI_MANAGED_STANDARD%40%40STANDARD&priceId=5dc0f84f4f13491e87d9b57d6bbeed2c) | Temperature and Humidity Sensor | 1 | $0.57 | $0.57 | [Alibaba](https://www.alibaba.com/product-detail/DHT11-Digital-Temperature-and-Humidity-Sensor_1600053358031.html?spm=a2700.prosearch.normal_offer.d_image.100167afkOugAf&selectedCarrierCode=SEMI_MANAGED_STANDARD%40%40STANDARD&priceId=5dc0f84f4f13491e87d9b57d6bbeed2c) |
| [Cherry MX Mechanical Key](https://www.alibaba.com/product-detail/MX-Cherry-Mechanical-Keyboard-with-Black_1601730062197.html?spm=a2700.prosearch.normal_offer.d_image.c71e67afYj58Pa&priceId=5b7ed05e44824c09ab1f91de8e6c2473) | Mechanical Push Buttons, for Control | 2 | $0.15 | $0.30 | [Alibaba](https://www.alibaba.com/product-detail/MX-Cherry-Mechanical-Keyboard-with-Black_1601730062197.html?spm=a2700.prosearch.normal_offer.d_image.c71e67afYj58Pa&priceId=5b7ed05e44824c09ab1f91de8e6c2473) |
| [Seeed XIAO ESP32-C3](https://www.alibaba.com/product-detail/Seeed-Studio-XIAO-ESP32C6-ESP32S3-ESP32S3_1601286855889.html?spm=a2700.prosearch.normal_offer.d_image.4cab67af7E0ApD&priceId=027e427a3ce74c9d8ac60624764c62b1) | Micro-Controller | 1 | $5.84 | $5.84 | [Alibaba](https://www.alibaba.com/product-detail/Seeed-Studio-XIAO-ESP32C6-ESP32S3-ESP32S3_1601286855889.html?spm=a2700.prosearch.normal_offer.d_image.4cab67af7E0ApD&priceId=027e427a3ce74c9d8ac60624764c62b1) |
| [PCB](https://cart.jlcpcb.com/quote?rand=0.4319600932958766) | Board | 1 | $8.40 | $8.40 | [JLCPCB](https://cart.jlcpcb.com/quote?rand=0.4319600932958766) |
| **Parts subtotal** | — | — | — | **$17.35** | — |
| **Tax & shipping** | — | — | — | **$10.00** | — |
| **Total** | — | — | — | **$27.35** | — |

## Social

Here are the short videos that I have posted related to my project (YouTube Shorts):

- **Idea:** https://www.youtube.com/shorts/dOhUSb0GdCU
- **5 Hours Progress:** https://www.youtube.com/shorts/tnYaCUamZv8

[#hackclubhalflife](https://www.youtube.com/hashtag/hackclubhalflife)
[#hackclub](https://www.youtube.com/hashtag/hackclub)
