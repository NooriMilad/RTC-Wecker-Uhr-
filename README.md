# RTC-Wecker-Uhr-
die Verbindungen zwischen dem ESP32 NodeMCU, dem RTC-Modul (DS3231) und dem LCD1602-Display mit I2C-Schnittstelle zu sehen:
ESP32 NodeMCU:
GPIO 21 (SDA) -> SDA (RTC und LCD)
GPIO 22 (SCL) -> SCL (RTC und LCD)
3.3V -> VCC (RTC und LCD)
GND -> GND (RTC und LCD)
