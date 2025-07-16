# Home-assistant-blueprints
Blueprints für Temperatur-basierte Fenster- und Lüftungsautomatisierung in Home Assistant
# Lüften & Fenster schließen (Blueprint für Home Assistant)

Dieser Blueprint sendet Benachrichtigungen zum Lüften oder Fenster-Schließen basierend auf dem Temperaturunterschied zwischen Innen- und Außensensoren.

## 🔧 Funktionen
- Zwei konfigurierbare Uhrzeiten (z. B. morgens & abends)
- Auswahl aktiver Wochentage
- Konfigurierbare Temperaturdifferenzen für Lüften und Schließen
- Mehrfachauswahl von mobilen Geräten für Push-Nachrichten
- Anhaltende Benachrichtigung (Companion App, optional)
- Alexa-Sprachausgabe (alexa_media, optional)

## 📥 Import in Home Assistant

Du kannst diesen Blueprint direkt über My Home Assistant importieren:

   [Blueprint direkt importieren](https://my.home-assistant.io/redirect/blueprint_import/?repository_url=https://raw.githubusercontent.com/Noack1978/Home-assistant-blueprints/main/lueften_fenster_automation.yaml)


## 🗂️ Ablageort

Pfad im Repository:
```
blueprints/automation/Noack1978/lueften_fenster_automation.yaml
```

## 📝 Hinweise

- Kompatibel mit `mobile_app` Geräten
- Funktioniert mit `alexa_media` Integration
- Unterstützt `persistent` Benachrichtigungen mit Notification-ID
