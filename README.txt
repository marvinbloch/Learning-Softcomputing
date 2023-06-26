Ordner Random:
	- Die Datei "random.ipynb" erzeugt Zufallsdaten aus dem excel-Sheet "daten.xlsx"
	- Die Zufallsdaten orientieren sich am Mietspiegel 2021 (zusehen in /Quellen)	
    - Ablauf:
        - Iterieren über alle Plz
            - Zu jeder Plz wir eine Zufällige Anzahl an Objekten erstellt
                - Für jedes Objekt wir ein Zufalls Baujahr und Zufalls Quadratmeter Attribut erstellt
                - Folgend werden zwei Indizes erfasst zu den Baujahr und Quadratmeter Attribut, um später die Miete zu ermitteln
                - Aus dem Quadratmeter Attribut lässt sich die Raumanzahl ermitteln
                - Aus dem Baujahr lässt sich die Energieeffizienzklasse ermitteln
                - Zu guter letzt wir aus den beiden Indizes einer gebildert aus dem sich der Mietspiegel ablesen lässt und somit die Range der Miete
                - Die Miete wir Zufällig im Range des Mietspiegels ermittelt
    