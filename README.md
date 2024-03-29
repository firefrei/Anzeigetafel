# Anzeigetafel
Ein simpler Webservice, mit dem Text auf einer Anzeigetafel dargestellt werden kann.
Das Skript basiert auf JavaScript und HTML5. Es ist für die Anzeige von Text auf einem Display oder mittels Projektor/Beamer auf einer Wand entwickelt worden. 
Hierbei können beliebig viele Textzeilen eingefügt und im Vollbildmodus angezeigt werden. Die Schriftgröße passt sich an die Anzahl der eingefügten Zeilen an (-> weniger Text, größere Schrift). Ist die letzte Zeile leer, wird diese automatisch ausgeblendet. Durch Hinzufügen von mehr als einer Leerzeile, kann die Schriftgröße entsprechend angepasst werden.

Mit dem Skript können beispielsweise Lieder in einer Kirche oder Informationen in einem Schaufenster angezeigt werden. Es wurde für eine Bedienung ohne tiefgründige IT Kenntnis ausgelegt.

Die Daten können bei Bedarf auch gespeichert werden. Hierfür wird im 'Local Storage' des Browsers eine SQLite Datenbank angelegt.
Zusätzlich kann auch eine Projektor-Fernsteuerung. sofern diese über eine Webseite erreicht werden kann, eingeblendet werden.

Screenshots:
https://raw.githubusercontent.com/FireFrei/Anzeigetafel/master/screenshots/Bearbeitungsmodus.jpg
https://raw.githubusercontent.com/FireFrei/Anzeigetafel/master/screenshots/Vollbildmodus.jpg


# Bedienung
- 'index.html' in einem Browser öffnen
- Textzeilen einfügen
- 'Projektion starten' klicken
- (Bei Bedarf 'Speichern' klicken)


# Konfiguration
- Die Formatierung des Vollbildmodus kann im CSS-Element '#anzeige-container' (index.html) bei Bedarf angepasst werden.
- Die URL für die Projektor-Fernsteuerung kann im HTML-Quelltext im Bereich '<!-- Modal: Beamer Fernbedienung -->' eingetragen werden.
- Das obere Logo kann in der Datei '/img/logo.png' ersetzt werden


# Autor
Matthias Frei
www.frei.media