Boost Power Converter XL6009 (https://www.amazon.de/dp/B06ZYYC99S/)
Spannungsanpassung:
Tests auf die Probe : 
in: 5V    out: 12V   0.8A    9.6W 
Eingangsspannung: 3,2 V-42V 
Ausgangsspannung: 5 V-35V 
Leistungsstarke Spannungsversorgung für da er bis zu 3 Ampere aushält

USB Netzteil Stecker (https://www.amazon.de/dp/B07RP5LBC1/)
Typ: 2-Port USB-Ladegerät
Eingang: AC 100-240V, 50/60 Hz
Ausgang: DC 5V / 2.1A.

Nimaso USB Typ C Kabel 3A (https://www.amazon.de/dp/B07Z9YW8GM/)
Ladeunterstützung bis zu 5V/3A und Datenübertragung in Hochgeschwindigkeit bewältigen 480Mbps.
56 kΩ eingebauter Widerstand für sichere Aufladung.

Lochrasterplatte Lochrasterplatine Leiterplatte (https://www.amazon.de/dp/B078HV79XX/)
Standard-Lochabstand von 2,54 mm (0,1 inch)
Flexibles Bestücken durch beidseitig mögliches Verlöten.
M2-Montagelöcher

2.7inch e-Paper HAT
Versorgungsspannung 5V (3.3V ginge auch) 
Kommunikation über SPI interface, siehe: https://www.waveshare.com/wiki/2.7inch_e-Paper_HAT
Wegen der 5V Versorgespannung müssen wahrscheinlich alle Ausgangssignale per hochohmigen 2:1 Spannungsteiler auf einen maximalwert von 3.3V herruntergeregelt 
werden bevor sie an den ESP angelegt werden.

Temperatursonde DS18B20
Versorgungsspannung 5V (alternativ gingen auch 3.3V)
Ausgang: Digitalwert (One-Wire-Bus). Der Ausgang wird sicherheitshalber per Spannungsteiler auf 3.3V Maximalwert gebracht (Annahme Digitalwerte sind bis zu 5V)
Es muss getestet werden ob das One-Wire-Bus Programm damit korrekt funktioniert.

Bodenfeuchtigkeitssensor Modul v1.2
Versorgespannung: 5V 
Ausgang: Analogwert, per Spannungsteiler auf Maximalwert 5V bringen.

Mit dem Spannungsteiler auf 3.3V runterregeln und ausprobieren!
analog Bodenfeuchtesensor auf 3.3V --> Wie müssen die Werte interpretiert werden? Testen welcher Spannungsoutput bei 5 VCC.
digital Temperatursensor auf 3.3V
Durchflussensor, Testen bei 3mm Schlauch 5-10cm abschneiden und für eine Wasserstandhöhe von 10 cm testen wie viel rausläuft --> Falls es zu langsam ist
