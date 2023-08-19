<p align="center">
  <img src="/images/wled_logo_akemi.png">
  <a href="https://github.com/Aircoookie/WLED/releases"><img src="https://img.shields.io/github/release/Aircoookie/WLED.svg?style=flat-square"></a>
  <a href="https://raw.githubusercontent.com/Aircoookie/WLED/master/LICENSE"><img src="https://img.shields.io/github/license/Aircoookie/wled?color=blue&style=flat-square"></a>
  <a href="https://wled.discourse.group"><img src="https://img.shields.io/discourse/topics?colorB=blue&label=forum&server=https%3A%2F%2Fwled.discourse.group%2F&style=flat-square"></a>
  <a href="https://discord.gg/KuqP7NE"><img src="https://img.shields.io/discord/473448917040758787.svg?colorB=blue&label=discord&style=flat-square"></a>
  <a href="https://kno.wled.ge"><img src="https://img.shields.io/badge/quick_start-wiki-blue.svg?style=flat-square"></a>
  <a href="https://github.com/Aircoookie/WLED-App"><img src="https://img.shields.io/badge/app-wled-blue.svg?style=flat-square"></a>
  <a href="https://gitpod.io/#https://github.com/Aircoookie/WLED"><img src="https://img.shields.io/badge/Gitpod-ready--to--code-blue?style=flat-square&logo=gitpod"></a>

  </p>
# Willkommen bei meinem Projekt WLED! ✨

Eine schnelle und funktionsreiche Implementierung eines ESP8266/ESP32-Webservers zur Steuerung von NeoPixel (WS2812B, WS2811, SK6812) LEDs sowie auch von SPI-basierten Chipsätzen wie den WS2801 und APA102!

## ⚙️ Funktionen
- WS2812FX-Bibliothek mit über 100 Spezialeffekten  
- FastLED-Rauscheffekte und 50 Paletten  
- Moderne Benutzeroberfläche mit Farb-, Effekt- und Segmentsteuerungen  
- Segmente zur Zuweisung verschiedener Effekte und Farben für benutzerdefinierte Teile der LED-Kette  
- Einstellungsseite - Konfiguration über das Netzwerk  
- Zugriffspunkt- und Stationsmodus - automatischer Failsafe-Zugriffspunkt  
- Bis zu 10 LED-Ausgänge pro Instanz  
- Unterstützung für RGBW-Streifen  
- Bis zu 250 Benutzer-Voreinstellungen, um Farben/Effekte einfach zu speichern und zu laden, unterstützt das Durchschalten von ihnen  
- Voreinstellungen können verwendet werden, um API-Aufrufe automatisch auszuführen  
- Nachtlichtfunktion (allmähliches Abdunkeln)  
- Volle OTA-Softwareaktualisierbarkeit (HTTP + ArduinoOTA), passwortgeschützt  
- Konfigurierbare Analoguhr (Cronixie, 7-Segment und EleksTube IPS-Uhrunterstützung über Benutzermodifikationen) 
- Konfigurierbare automatische Helligkeitsbegrenzung für sicheren Betrieb  
- Konfiguration über Dateisystem für einfachere Sicherung von Voreinstellungen und Einstellungen  

## 💡 Unterstützte Lichtsteuerungsschnittstellen
- WLED-App für [Android](https://play.google.com/store/apps/details?id=com.aircoookie.WLED) und [iOS](https://apps.apple.com/de/app/wled/id1475695033)
- JSON- und HTTP-Anfrage-APIs  
- MQTT   
- E1.31, Art-Net, DDP und TPM2.net
- [diyHue](https://github.com/diyhue/diyHue) (WLED wird von diyHue unterstützt, einschließlich Hue Sync Entertainment über UDP. Dank an [Gregory Mallios](https://github.com/gmallios))
- [Hyperion](https://github.com/hyperion-project/hyperion.ng)
- Echtzeit-UDP  
- Alexa-Sprachsteuerung (einschließlich Dimmen und Farbsteuerung)  
- Synchronisation mit Philips Hue-Lampen  
- Adalight (PC-Ambilight über serielle Verbindung) und TPM2  
- Farbsynchronisation mehrerer WLED-Geräte (UDP-Benachrichtigungsdienst)  
- Infrarot-Fernbedienungen (24-Tasten-RGB, Empfänger erforderlich)  
- Einfache Timer/Zeitpläne (Zeit von NTP, Zeitzonen/DST unterstützt)  

## 📲 Schnellstartanleitung und Dokumentation

Siehe die [Dokumentation auf unserer offiziellen Website](https://kno.wled.ge)!

[Auf dieser Seite](https://kno.wled.ge/basics/tutorials/) finden Sie ausgezeichnete Anleitungen und Tools, die Ihnen helfen, Ihr neues Projekt in Betrieb zu nehmen!

## 🖼️ Benutzeroberfläche
<img src="/images/macbook-pro-space-gray-on-the-wooden-table.jpg" width="50%"><img src="/images/walking-with-iphone-x.jpg" width="50%">

## 💾 Kompatibles Hardware

Siehe [hier](https://kno.wled.ge/basics/compatible-hardware)!

## ✌️ Sonstiges

Lizenziert unter der MIT-Lizenz  
Credits [hier](https://kno.wled.ge/about/contributors/)!

Treten Sie dem Discord-Server bei, um alles rund um WLED zu besprechen!

<a href="https://discord.gg/KuqP7NE"><img src="https://discordapp.com/api/guilds/473448917040758787/widget.png?style=banner2" width="25%"></a>

Schauen Sie sich das WLED-[Discourse-Forum](https://wled.discourse.group) an!  

Sie können mir auch E-Mails senden an [dev.aircoookie@gmail.com](mailto:dev.aircoookie@gmail.com), aber bitte nur, wenn Sie privat mit mir sprechen möchten.  

Wenn WLED Ihren Tag wirklich aufhellt, können Sie mir [![](https://img.shields.io/badge/send%20me%20a%20small%20gift-paypal-blue.svg?style=flat-square)](https://paypal.me/aircoookie) eine kleine Spende über PayPal zukommen lassen.

*Haftungsausschluss:*

Wenn Sie anfällig für photosensitive Epilepsie sind, empfehlen wir Ihnen, diese Software **nicht** zu verwenden.  
Wenn Sie es dennoch ausprobieren möchten, verwenden Sie keine Stroboskop-, Beleuchtungs- oder Geräuschmodi oder hohe Effektgeschwindigkeitseinstellungen.

Gemäß der MIT-Lizenz übernehme ich keine Haftung für Schäden an Ihnen oder anderen Personen oder Geräten.


