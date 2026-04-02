# Spotify Display Device

## Description
This project is a WiFi-enabled Spotify display that shows the currently playing song on a TFT screen.

## Why I Made This
I built this project to learn embedded systems and create a physical interface for Spotify playback.

## Project Photos
no materials yet

## 3D Model
https://github.com/calebwu325-dot/legendary-winner/blob/449a392221c0135828b6b92257e0e043b42f2298/case.stl
<img width="840" height="778" alt="Screenshot 2026-04-01 224054" src="https://github.com/user-attachments/assets/2a16d7d7-d219-43d5-a69d-e562b483e885" />
<img width="1168" height="941" alt="Screenshot 2026-04-01 224129" src="https://github.com/user-attachments/assets/7c7e7ce9-2753-48ae-9ae1-5041f15062c7" />
<img width="1194" height="921" alt="Screenshot 2026-04-01 224136" src="https://github.com/user-attachments/assets/d36852a2-e346-47e8-97ef-61d9e3f0983c" />



## Wiring Diagram
| TFT Pin | ESP32 Pin | Description |
|--------|----------|-------------|
| VCC | 3.3V | Power supply |
| GND | GND | Ground |
| CS | GPIO 1 | Chip select |
| RST / RES | GPIO 2 | Reset |
| DC / A0 | GPIO 3 | Data/command control |
| SCL / SCK | GPIO 4 | SPI clock |
| SDA / MOSI | GPIO 5 | SPI data |
| LED / BL | 3.3V | Backlight power |

## Bill of Materials (BOM)

| Name | Purpose | Quantity | Total Cost (USD) | Link | Distributor |
|------|--------|----------|------------------|------|-------------|
| REDRAGON SMD RGB Outemu MX Switch | Input buttons | 1 | $3.98 | Link to Listing | AliExpress |
| 1.8" 128x160 SPI Full Color TFT LCD Display Module | Displays the Spotify song | 1 | $5.34 | Link to Listing | AliExpress |
| C3 Mini V2.1.0 LOLIN WiFi Bluetooth LE BLE IoT Board | Microcontroller to connect components and run software | 1 | $5.47 | Link to Listing | AliExpress |
| Anycubic Water Wash Resin 3.0 | Material for 3D printing the case | 1 | $20.98 | Link to Listing | Amazon |

### Total Cost
**$35.77** (excluding tax and shipping)
