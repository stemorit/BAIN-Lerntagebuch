---
title: "2 Funktion und Aufbau von Bibliothekssystemen"
date: 2020-09-25
---
**MARC21 vs. Dublin Core**

Wir haben eine Übung gemacht und uns die Unterschiede zwischen den Metastandards *MARC21* und *Dublin Core* angeschaut. In dieser Tabelle sind die Ergebisse aus der Vorlesung und noch ein paar Zusatzinformationen aus der Recherche festgehalten.

| MARC21                              | DC  | 
| -------------                       |---------------| 
| Machine-Readable Cataloging         | Dublin Core | 
| 1960                              | 1994     |  
| bibliographisches Dateiformat welches verwendet wird, um bibliographische Daten zwischen verschiedenen Einrichtungen auszutauschen                        | Sammlung an standardisierten Konventionen für eine einfache Beschreibung von Dokumenten und anderen verwandten Objekten im Web mithilfe von bibliographischen Metadaten      | 
|<img alt="MARC" src="https://github.com/stemorit/BAIN-Lerntagebuch/blob/master/_posts/MARC21.png?raw=true" width="80%"/> | <img alt="DC" src="https://github.com/stemorit/BAIN-Lerntagebuch/blob/master/_posts/DC.png?raw=true" width="80%"/>|
|schwierige Tags und Zahlencodes  |  leicht verständliche Namespaces  |
| schwer verständlich für Menschen ohne Vorkentnisse | einfacher verständlich für Menschen ohne Vorkentnisse|
| wird in Bibliothekssystemen genutzt | wird eher weniger in Bibliothekssystemen genutzt als MARC21|

Quellen: [forschungsdaten.info](https://www.forschungsdaten.info/themen/beschreiben-und-dokumentieren/bibliographische-metadaten/), 2. Unterrichtslektion und Folien.

Bild MARC21: [sru.swissbib.ch/MARC21](https://sru.swissbib.ch/sru/search/defaultdb?query=+dc.possessingInstitution+%3D+E27+AND+dc.title+%3D+open+access&operation=searchRetrieve&recordSchema=info%3Asrw%2Fschema%2F1%2Fmarcxml-v1.1-light&maximumRecords=10&startRecord=0&recordPacking=XML&availableDBs=defaultdb&sortKeys=Submit+query)

Bild Dublin Core: [sru.swissbib.ch/Dublin Core](https://sru.swissbib.ch/sru/search/defaultdb?query=+dc.possessingInstitution+%3D+E27+AND+dc.title+%3D+open+access&operation=searchRetrieve&recordSchema=info%3Asru%2Fschema%2F1%2Fdc-v1.1-light&maximumRecords=10&startRecord=0&recordPacking=XML&availableDBs=defaultdb&sortKeys=Submit+query)


**Installation und Konfiguration von Koha**


Was ist Koha? Koha ist das erste freie und quelloffene Bibliothekssystem der Welt. Koha ist ein voll ausgestattetes, skalierbares Bibliotheksverwaltungssystem. Die Entwicklung wird von Bibliotheken unterschiedlicher Art und Größe, Freiwilligen und unterstützenden Unternehmen weltweit gesponsert [Quelle: koha-community.org](https://koha-community.org/).

Die Installation von Koha ging erstaunlich gut. Ich hatte keine Probleme damit. 


<img alt="koha" src="https://github.com/stemorit/BAIN-Lerntagebuch/blob/master/_posts/Koha_funktioniert.png?raw=true" width="70%"/>


Die Einstellungen aus dem [Tutorial](https://zefanjas.de/wie-man-koha-installiert-und-fuer-schulen-einrichtet-teil-1/)vorzunehmen war sehr eindrücklich. Ich brauche es zwar jeden Tag aber ich hätte nicht gedacht, dass es so viele unterschiedliche Einstellungen hinter einem Bibliothekssystem hat. Ich habe mir darüber nie Gedanken gemacht, aber wenn man mal sieht was man da alles einstellen kann und muss ist es schon ein bisschen überwältigend. Alleine bei den Systemparametern gibt es 17 Kategorien, bei denen jedes wieder Unterkategorien hat mit Werten, die eingestellt werden können. Das mal zu sehen und auszuprobieren war für mich bereits eine Bereicherung. Ich werde vermutlich nie Systemadministratorin werden, aber doch ist es interessant sich bewusst zu machen, was da alles dahinter steckt. Das erwähnte Tutorial war übrigens gut zu meistern. Vor allem am Anfang war alles sehr gut beschrieben. Gegen Ende (3. Kapitel) nicht mehr so. Eine Einstellung aus dem Tutorial konnte ich nicht finden bei den Systemparametern unter OPAC „OpacMainUserBlock“ dort hätte ich eine Willkommensnachricht für die Hauptseite schreiben wollen. Leider habe ich nach dreimaligem Durchsehen der Einstellungen diesen Parameter immer noch nicht gefunden, vielleicht wurde der Name geändert. Aber alles in Allem sonst eine gute Erfahrung, *"die wichtigsten Grundeinstellungen in Koha sind abgearbeitet, es ist nun soweit eingerichtet, dass die ersten Bücher aufgenommen und ausgeliehen werden können."* Zumindest sagt das das Fazit vom Tutorial. Das war ein tolle Erfolgserlebnis im Modul Bibliotheks- und Archivinformatik. 

Ich freue mich auf den zweiten Teil von „Funktion und Aufbau von Bibliothekssystemen“.


