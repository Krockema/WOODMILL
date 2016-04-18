![GitHub Logo](http://www.heise.de/make/icons/make_logo.png)

Maker Media GmbH und c't, Heise Zeitschriften Verlag

***

#c't Hacks & Make: Sperrholzfr�se

###Einfach aufzubauende, CNC-gesteuerte Portalfr�se aus Holz- und Fertigbauteilen

Zum Download der DesignSpark-Pl�ne "View raw" anklicken. Sie ben�tigen zur Weiterverarbeitung das kostenlose **[DesignSpark Mechanical](http://www.designspark.com/deu/page/mechanical)**. Sketchup-File ist ein Export aus DesignSpark, kann Ungenauigkeiten enthalten. Bitte beachten Sie unbedingt den Artikel in **[c't Hacks 1/2014](http://heise.de/-2109420)**.

Das aus Designspark Mechanical exportierte PDF enth�lt keine Bema�ungen. Zur Anzeige ist ein neuerer Acrobat Reader mit aktivierter 3D-Ansicht erforderlich. 

Die Make: Sperrholzfr�se wurde in der **[Dingfabrik K�ln](http://dingfabrik.de/)** in gr��erer St�ckzahl mit gutem Erfolg nachgebaut und auch in einigen Punkten verbessert. N�here Informationen unter **http://www.cnc14.de/**



###St�ckliste Holzzuschnitt

Wenn nicht anders angegeben, 18 mm Multiplex Buche oder Birke

* 1 St�ck 1000 x 600 mm (Grundplatte)
* 2 St�ck 1000 x 70 mm (Grundplatte Erh�hung f�r Linearf�hrungen)
* 4 St�ck 600 x 70 mm (Versteifungen Grundplatte, unten)
* 1 St�ck 600 x 200 mm (Y-Schlitten)
* 2 St�ck 200 x 70 mm (Y-Schlitten Erh�hung f�r Linearf�hrungen, unten)
* 1 St�ck 220 x 200 mm (Z-Tr�gerplatte senkrecht)
* 1 St�ck 210 x 200 mm (Z-Tr�gerplatte waagerecht)
* 2 St�ck 170 x 140 mm (Z-Tr�gerplatte Versteifungen)
* Motorhalterung X-Achse aus Multiplex-Resten, oder
 * 2 St�ck 100 x 60 mm
 * 2 St�ck 64 x 60 mm
 * 1 St�ck 100 x 100 mm Hartfaserplatte 4 oder 5 mm

###St�ckliste Mechanik

* 3 Schrittmotoren NEMA 23, min. 1,5 A Strangstrom
* 2 Zahnriemenscheiben 16 Z�hne, z.B. Ebay-Anbieter f�r RepRap-Zubeh�r; ggf. aufbohren auf Achsdurchmesser!
* 5 m Zahnriemen T2,5 x 6 mm, Stahl-Zugstrang, Meterware, z.B. Ebay-Anbieter f�r RepRap-Zubeh�r
* 1 Wellenkupplung 6,35/8 mm flexibel, z.B. von [CNC-Discount](http://www.cnc-discount.de/epages/62924595.sf/de_DE/?ObjectPath=/Shops/62924595/Products/%225NM%20%22%22klein%22%22%20%206%2C35%20/%208mm%22) oder [Dold Mechatronik](http://www.dold-mechatronik.de/Wellenkupplung-RB-flexibel-D20L25-635-800mm)
* 10 Kugellager 636-2RS (6 x 22 x 6 mm) z.B. von [Kugellager-Express](http://www.kugellager-express.de/Miniatur-Kugellager-/Miniatur-Kugellager-6--/-Miniatur-Kugellager---636---636z---636rs---6x22x7-mm.html)
* 20 Karosseriescheiben M6, Durchmesser 25 mm
* 20 Unterlegscheiben M6 d�nn, oder Passscheiben 0,2 mm
* 2 Maschinenschrauben Innensechskant M6 x 80 (Umlenkrollen auf Y-Schlitten)
* 4 Maschinenschrauben Innensechskant M6 x 40 (Umlenkrollen)
* 4 Maschinenschrauben Innensechskant M6 x 30 (Befestigung Z-Achse)
* 12 Maschinenschrauben Innensechskant M5 x 16 (Schrittmotor-Befestigung)
* 16 Maschinenschrauben Innensechskant M5 x 25 (Linearlager-Befestigung Z-Schlitten)
* div. Unterlegscheiben, Muttern M5 und M6, Spax/Universalschrauben, Kleinteile, vom Baumarkt
* 1 CNC Set 20 x 1000mm breit, z.B. von [CNC-Discount, Ebay-Shop](http://www.cnc-discount.de) oder in Einzelteilen von [Dold Mechatronik](http://www.dold-mechatronik.de)
* 1 CNC Set 16 x 600mm schmal, z.B. von [CNC-Discount, Ebay-Shop](http://www.cnc-discount.de) oder in Einzelteilen von [Dold Mechatronik](http://www.dold-mechatronik.de)
* 1 Z-Achse, fertig aufgebaut, Ebay-Angebot Fa. Anton Schelkopf electronic

Pl�ne als PDF und f�r **[DesignSpark Mechanical](http://www.designspark.com/deu/page/mechanical)** gepackt als ZIP. 
Bema�ung aus editierbarem DesignSpark-Entwurf ersichtlich (Beschriftungsebenen einblenden!)

Es ist m�glich, die recht teuren Kugelwagen-Linearf�hrungen mit leichten Modifikationen (zus�tzliche Brettchen zur 
Erh�hung) durch die preiswerten DryLin-Gleitschienen Typ N in 27 und 40 mm Breite von 
[Igus](http://www.igus.de/wpck/1969/drylin_n) zu ersetzen (CAD-Daten anbei). Hierbei ist aber auf einen stabilen, 
verwindungssteifen Unterbau der Fr�se zu achten, da diese Gleitschienen im Unterschied zu den Stahlwellen weniger steif 
sind.

###Wichtige Hinweise zu GRBL

Wir empfehlen zur Ansteuerung **GRBL 0.9j** f�r Arduino (angepasstes HEX-File samt Sourcen in **GRBL_arduino.ZIP** enthalten) oder unsere speziell angepasste **GRBL-JOG**-Platine.

Bitte beachten Sie, dass bei einigen chinesischen Schrittmotortreibern die Belegungen der XYZ-Step/Direction-Pins 
vertauscht sind. Auf der GRBL-JOG-Platine sind dann die Leiterbahnen unter den Pfostenleisten PL9 und 10 
aufzutrennen und die Verbindungen mit Jumper-Kabeln in der richtigen Reihenfolge herzustellen. Anleitungen zu 
verschiedenen Treiberkarten finden Sie in unserem Github-Repository TB6560-BOARDS.

Die Schrittmotor-Endstufen mit TB6560 und TB6600 ben�tigen eine kurze Verz�gerungszeit zwischen Umschalten der Richtung und dem ersten Schritt-Impuls, ansonsten k�nnen Schritte verlorengehen. Unbedingt in config.h der GRBL-Sourcen die Zeile

 #define STEP_PULSE_DELAY 10 // Step pulse delay in microseconds. Default disabled.

aktivieren und GRBL neu kompilieren, wenn Sie nicht die kompilierte HEX-File aus dem beigef�gten GRBL_arduino.ZIP verwenden.

Das CNC-Steuerungsprogramm aus c't Hacks 4/2014 finden Sie in unserem Github-Repo **[GRBLize](https://github.com/heise/GRBLize)**.

Carsten Meyer, Redaktion c't Hacks, Make Deutschland (cm@ct.de)