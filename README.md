# Jontes Aquariumspiel 🐟

"Jontes Aquariumspiel" ist eine webbasierte, interaktive Wirtschaftssimulation, die mit HTML, JavaScript und Tailwind CSS umgesetzt wurde. Spieler verwalten ein Aquarium, kaufen Tiere und Dekorationen, optimieren das Wachstum der Bewohner und pflegen das Becken.

## Features

* **Wirtschaftssystem:** Startkapital von 20,00 €. Kauf von Fischen, Pflanzen und Dekorationen. Verkauf von Tieren bringt Gewinn.
* **Wachstum & Zucht:**
    * Tiere wachsen durch Fütterung und steigern so ihren Verkaufswert.
    * Automatisierte Zucht: Bei optimalen Bedingungen vermehren sich Tiere im Becken.
* **Wartung:**
    * **Algen-System:** Über Zeit bildet sich ein Algenfilm, der mit dem Schwamm-Werkzeug manuell entfernt werden muss.
    * **Fütterung:** Dynamische Futterpartikel, die sinken und von Tieren aktiv gejagt werden.
* **Interaktionen & Ereignisse:**
    * **Kescher-Modus:** Fangen von Tieren für das Inventar (Plastikbeutel-Darstellung).
    * **Seltene Events:** Gelegentliche Preisnachlässe auf bestimmte Tierarten.
    * **Besondere Bewohner:** Zufälliges Erscheinen eines Röhrenaals.
* **Dev Tools:** Integriertes Entwickler-Panel für Debugging (Spawnen von Aal, Algen, Tieren oder Budget-Anpassung).

## Steuerung

| Aktion | Steuerung |
| :--- | :--- |
| **Platzieren** | Drag & Drop aus der Werkzeugleiste in das Becken. |
| **Füttern** | Klick auf die Futterdose (0,20 €). |
| **Fangen** | Kescher-Modus aktivieren, dann Klick auf das Tier. |
| **Reinigen** | Schwamm-Modus aktivieren, über Algen auf dem Becken wischen. |
| **Verkaufen** | Gefangene Tiere im Inventar per "Verkaufen"-Button liquidieren. |

## Technische Details

* **Frontend:** Tailwind CSS für das Styling.
* **Logik:** Reines JavaScript (Vanilla JS).
* **Grafik:** Alle Elemente sind als Inline-SVGs realisiert.
* **Rendering:** Dynamisches Canvas-Rendering für den Algenbefall.

## Entwicklung

Dieses Projekt ist als Standalone-Anwendung konzipiert und läuft in modernen Browsern ohne zusätzliche Abhängigkeiten.

### Dev-Panel Funktionen
Das Entwickler-Panel ermöglicht direkten Zugriff auf Spielparameter:
- `Tier-Event`: Manuelles Auslösen der Rabatt-Mechanik.
- `Spawne Röhrenaal`: Erzwingt das Erscheinen des seltenen Röhrenaals.
- `+ 20 €`: Manuelle Budget-Erhöhung.
- `Algen spawnen`: Simuliert Algenbefall zu Testzwecken.

---

Viel Spaß beim Spielen! 🐠
