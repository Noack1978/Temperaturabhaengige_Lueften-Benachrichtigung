# Home-assistant-blueprints
Blueprints für Temperatur-basierte Fenster- und Lüftungsautomatisierung in Home Assistant
# Lüften & Fenster schließen (Blueprint für Home Assistant)

Dieser Blueprint sendet Benachrichtigungen zum Lüften oder Fenster-Schließen basierend auf dem Temperaturunterschied zwischen Innen- und Außensensoren.

## 🔧 Funktionen
- Zwei konfigurierbare Uhrzeiten (z. B. morgens & abends)
- Auswahl aktiver Wochentage
- Konfigurierbare Temperaturdifferenzen für Lüften und Schließen
- Mehrfachauswahl von mobilen Geräten für Push-Nachrichten (optional) 
- Anhaltende Benachrichtigung (Companion App, optional)
- Alexa-Sprachausgabe (alexa_media, optional)
- Konfigurierbare Mindest-Innentemperatur zur Auslösung der Benachrichtigungen
- **Neu**: Optionale Benachrichtigung, wenn Fenster länger als X Minuten offen bei zu warmer Außentemperatur

## 📥 Import in Home Assistant

Du kannst diesen Blueprint direkt über My Home Assistant importieren:

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https://github.com/Noack1978/Home-assistant-blueprints/blob/main/lueften_fenster_automation.yaml)

Oder folgende URL kopieren und in home assistant manuell importieren
```
https://raw.githubusercontent.com/Noack1978/Home-assistant-blueprints/main/lueften_fenster_automation.yaml
```

## 📝 Hinweise

- Kompatibel mit `mobile_app` Geräten
- Funktioniert mit `alexa_media` Integration
- Unterstützt `persistent` Benachrichtigungen mit Notification-ID
