# Rikus Weather

**The weather on your Xfce or GNOME desktop — right on your wallpaper, from shimmering ceramic to liquid glass.**
Free of charge, no sign-up, no code.

➡️ **Website and download: https://weather.rikus.info**

---

## 🇬🇧 English

### What it does

Rikus Weather puts a weather card right onto your wallpaper: behind all windows, without a
button in the panel, on every workspace — like a look out of the window.

- **Now, hour by hour and the next five days** — temperature and how it feels, humidity, wind,
  precipitation, air pressure, UV index, visibility, sunrise and sunset. Every value can be
  switched on or off.
- **Any place you look up** — type a town or village and pick it from the list. The weather data
  comes from Open-Meteo, no account needed.
- **From ceramic to liquid glass:** one slider takes the card from shimmering ceramic to glass
  with your wallpaper shining through — as **clear glass**, **hologram** or **frosted glass**.
- **Three kinds of tiles:** glaze, floating and soap bubble.
- **Nine fixed spots** or drag the card anywhere with the mouse. Size from 70 to 140 percent,
  four colours or one of your own, light and dark — dark is anthracite, never black.
- **A right-click** on the card opens the settings.
- The card speaks **German or English** — just as your computer is set.

### Install (Xfce — for example Debian 13 with Xfce)

Add the package repository once:

```sh
sudo install -d /etc/apt/keyrings && sudo curl -fsSL https://apt.rikus.info/rikus-apt.gpg -o /etc/apt/keyrings/rikus.gpg
echo "deb [signed-by=/etc/apt/keyrings/rikus.gpg] https://apt.rikus.info stable main" | sudo tee /etc/apt/sources.list.d/rikus.list
```

Then install:

```sh
sudo apt update && sudo apt install rikus-weather
```

Then click “Rikus Weather” once in the start menu — from your next login on the card comes up
by itself. To remove the repository again (the card stays installed):

```sh
sudo rm /etc/apt/sources.list.d/rikus.list /etc/apt/keyrings/rikus.gpg && sudo apt update
```

Or download the file directly on **https://weather.rikus.info**.

### Install (GNOME 48 — for example Debian 13 with GNOME)

On GNOME the card is an extension of the desktop, in its own package **rikus-weather-gnome**.
Add the package repository as shown above, then install:

```sh
sudo apt update && sudo apt install rikus-weather-gnome
```

Then log out and back in once — the card is on your desktop. You switch it on and off under
**Extensions**. Please install it only on a GNOME desktop — on any other desktop it would bring
along the whole GNOME environment. Or download the file directly on **https://weather.rikus.info**.

### What you need

**The Xfce desktop** for the package rikus-weather — **or GNOME 48** for the package
rikus-weather-gnome — and an internet connection for the weather data. On other desktops such as
Cinnamon or KDE the card has not been tried out yet, and other GNOME versions neither. For the
see-through glass on Xfce, compositing has to be switched on.

### Current version

**1.0** (25 September 2026) — the first version, for Xfce (rikus-weather) and GNOME 48 (rikus-weather-gnome).
All changes, in German and English: https://weather.rikus.info/aenderungen

### Where the code lives

This page is the **contact point**, not the source archive. The program is delivered through
the website and the package repository above, not from here.
Use **Issues** for bug reports and questions — or write through the form on the website:
https://weather.rikus.info/schreiben

---

## 🇩🇪 Deutsch

### Was es macht

Rikus Weather stellt eine Wetterkarte direkt auf dein Hintergrundbild: hinter alle Fenster,
ohne Knopf in der Leiste, auf jede Arbeitsfläche — wie ein Blick aus dem Fenster.

- **Jetzt, Stunde für Stunde und die nächsten fünf Tage** — Temperatur und wie sie sich anfühlt,
  Luftfeuchtigkeit, Wind, Niederschlag, Luftdruck, UV-Index, Sichtweite, Sonnenaufgang und
  -untergang. Jeder Wert lässt sich einzeln ein- und ausschalten.
- **Jeder Ort, den du suchst** — Stadt oder Dorf eintippen und aus der Liste wählen. Die
  Wetterdaten kommen von Open-Meteo, ganz ohne Konto.
- **Von Keramik bis Liquid Glass:** Ein Regler führt die Karte von schimmernder Keramik bis zu
  Glas, durch das dein Hintergrundbild scheint — als **Klarglas**, **Hologramm** oder **Milchglas**.
- **Drei Kachel-Arten:** Glasur, Schwebend und Seifenblase.
- **Neun feste Stellen** oder die Karte mit der Maus hinziehen, wo du willst. Größe von 70 bis
  140 Prozent, vier Farben oder eine eigene, Hell und Dunkel — Dunkel ist Anthrazit, nie Schwarz.
- **Ein Rechtsklick** auf die Karte öffnet die Einstellungen.
- Die Karte spricht **Deutsch oder Englisch** — so, wie der Rechner eingestellt ist.

### Installieren (Xfce — zum Beispiel Debian 13 mit Xfce)

Die Paketquelle einmal eintragen:

```sh
sudo install -d /etc/apt/keyrings && sudo curl -fsSL https://apt.rikus.info/rikus-apt.gpg -o /etc/apt/keyrings/rikus.gpg
echo "deb [signed-by=/etc/apt/keyrings/rikus.gpg] https://apt.rikus.info stable main" | sudo tee /etc/apt/sources.list.d/rikus.list
```

Dann installieren:

```sh
sudo apt update && sudo apt install rikus-weather
```

Danach im Startmenü einmal auf „Rikus Weather“ klicken — ab dem nächsten Anmelden kommt die
Karte von selbst. Die Paketquelle wieder loswerden (die Karte bleibt installiert):

```sh
sudo rm /etc/apt/sources.list.d/rikus.list /etc/apt/keyrings/rikus.gpg && sudo apt update
```

Oder die Datei direkt auf **https://weather.rikus.info** herunterladen.

### Installieren (GNOME 48 — zum Beispiel Debian 13 mit GNOME)

Unter GNOME ist die Karte eine Erweiterung des Desktops, im eigenen Paket **rikus-weather-gnome**.
Die Paketquelle wie oben eintragen, dann installieren:

```sh
sudo apt update && sudo apt install rikus-weather-gnome
```

Danach einmal ab- und wieder anmelden — die Karte steht auf dem Desktop. Ein- und ausschalten
lässt sie sich bei den **Erweiterungen**. Bitte nur auf einem GNOME-Desktop installieren — auf
einem anderen Desktop würde es die ganze GNOME-Oberfläche mitbringen. Oder die Datei direkt auf
**https://weather.rikus.info** herunterladen.

### Was du brauchst

**Den Xfce-Desktop** für das Paket rikus-weather — **oder GNOME 48** für das Paket
rikus-weather-gnome — und eine Internetverbindung für die Wetterdaten. Auf anderen Oberflächen wie
Cinnamon oder KDE ist die Karte noch nicht erprobt, andere GNOME-Fassungen ebenfalls nicht. Damit
das Glas unter Xfce durchsichtig sein kann, muss das Compositing eingeschaltet sein.

### Aktuelle Fassung

**1.0** (25. September 2026) — die erste Fassung, für Xfce (rikus-weather) und GNOME 48 (rikus-weather-gnome).
Alle Änderungen, deutsch und englisch: https://weather.rikus.info/aenderungen

### Wo der Quelltext liegt

Diese Seite ist die **Anlaufstelle**, nicht das Archiv des Quelltextes. Das Programm kommt über
die Webseite und die Paketquelle oben, nicht von hier.
Fehler und Fragen bitte unter **Issues** — oder über das Formular auf der Webseite:
https://weather.rikus.info/schreiben

---

## More free programs / Weitere kostenlose Programme

All Rikus programs / Alle Rikus-Programme: **https://programme.rikus.info**

## Nutzungsbedingungen / Terms of use

Copyright (C) 2026 Gilbert Rikus. **Alle Rechte vorbehalten. All rights reserved.**

Benutzen ist kostenlos. Vervielfältigen, Verändern und Übernehmen in eigene Programme sind
**nicht** gestattet. Der vollständige Text liegt jedem Paket als `LICENSE` bei.

Use is free of charge. Copying, modifying and reusing it in your own programs are **not**
permitted. The full text ships with every package as `LICENSE`.

---

© Gilbert Rikus · https://rikus.info
