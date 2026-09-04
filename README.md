Zinseszins-Rechner

Ein einfacher, browserbasierter Rechner zur Berechnung des Zinseszinseffekts – ideal um zu sehen, wie sich ein Startkapital (und optional regelmäßige Einzahlungen) über einen bestimmten Zeitraum entwickelt.

🔗 Live-Demo: Hier ausprobieren

Funktionen
Berechnung des Endkapitals basierend auf Startkapital, Zinssatz und Laufzeit
Unterstützung regelmäßiger Einzahlungen (monatlich/jährlich)
Sofortige Berechnung im Browser – keine Serveranfrage nötig
Responsive Design für Desktop und Mobilgeräte
Verwendete Formel

Die Grundformel für den Zinseszinseffekt:

Endkapital = Startkapital × (1 + Zinssatz)^Jahre

Bei regelmäßigen Einzahlungen wird zusätzlich der Rentenendwert der Einzahlungen berücksichtigt:

Endkapital = Startkapital × (1 + r)^n + Einzahlung × [((1 + r)^n − 1) / r]

wobei r der periodische Zinssatz und n die Anzahl der Perioden ist.

Nutzung
Repository klonen oder index.html herunterladen
Datei im Browser öffnen – keine Installation notwendig
Startkapital, Zinssatz, Laufzeit und ggf. regelmäßige Einzahlung eingeben
Ergebnis wird direkt angezeigt

Technologien
HTML
CSS
JavaScript (Vanilla, keine Frameworks)
MIT License

Copyright (c) 2026 Simon

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Haftungsausschluss

Dieser Rechner dient ausschließlich zu Informationszwecken und stellt keine Finanzberatung dar. Alle Berechnungen basieren auf vereinfachten Annahmen (z.B. konstanter Zinssatz über die gesamte Laufzeit).
