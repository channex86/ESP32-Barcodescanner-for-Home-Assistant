# ESP32-Barcodescanner-for-Home-Assistant
Ein DIY-Barcodescanner bestehend aus einem ESP32-S3, einem GM60-Barcode-Modul, TFT-Display, Buzzer, usw...

Features:
- Barcodes scannen und in HA integrieren
- Echter Barcode-Beep als Rückmeldung
- Aufbau einer Grocy-Datenbank
- 3 Modis wählbar: Einkaufsliste, Produktregistrierung, Lagermodus

Hardware (getestet):
- ESP32-S3 oder ESP32 D1 Mini
- Barcode-Scannermodul GM60 oder GM861s
- 1.77" TFT (ST7735) oder 0.96" OLED-Display (SSD1306)
- Piezo-Buzzer (aktiv oder passiv möglich)
- Taster
- Status-LED-Platine (KY-016 FZ0455)
- Ultraschall-Sensor (HC-SR04) oder PIR-Präsenzsensor (HC-SR501). Der PIR ist allerdings nicht empfehlenswert. Lieber den HC-SR04 nehmen
- beliebige Leuchtstarke LED
- Lochrasterplatine 5x7cm
- jede Menge Dupont-Kabel
- ein paar Stift- und Buchsenleisten (2,54mm)


## License

This project is licensed under the Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0).

- Private use and adaptation permitted

- No commercial use without prior permission

## Lizenz

Dieses Projekt ist lizenziert unter der  
Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0).

- Private Nutzung und Anpassung erlaubt
- Keine kommerzielle Nutzung ohne vorherige Genehmigung

© 2026 channex86
