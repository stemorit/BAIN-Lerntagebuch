---
title: "1 Technische Grundlagen "
date: 2020-09-10
---


Der Einstieg in das Fach BAIN war hart für mich. Nicht weil ich vom Fach überhaupt nichts verstehe, sondern weil einfach diese Software wieder nicht funktioniert hat. Für das Einrichten der Arbeitsumgebung Linux wurden 20 Minuten eingeplant, für mich waren es eher 20 Stunden. Schon bevor das Fach am 10. September 2020 gestartet ist, hatte ich so eine Ahnung, dass wir die Virtuelle Maschine wieder brauchen werden. Schon im Modul ARIS (oder wars ein anderes Modul?) haben wir sie gebraucht. Bereits damals war die Installation extrem mühsam, daran hatte ich wirklich nur schlechte Erinnerungen. Mittlerweile muss man sich die virtuelle Maschine nicht mehr selbst herunterladen, sondern kann sich einfach mit dem Horizon Client einloggen. Da steht schon alles bereit, was ich sehr gut finde! Leider hat aber auch das bei mir nicht funktioniert. Die Verbindung mit dem Horizon Client wollte einfach nicht funktionieren. Am Tag davor hat es interessanterweise noch funktioniert, aber da habe ich mich im FHGR Gebäude befunden, was wie sich herausstelle auch der Grund war wieso es da noch funktioniert hat. 

Der Unterricht ging schon längst weiter und ich hatte immer noch keine Verbindung. Wir hätten eine Gruppenarbeit machen sollen mit der Unix Shell, aber ich musste mich mit dem Verbinden beschäftigen und habe das leider verpasst. Ich habe dann für mich selbst bestimmt, die Gruppenarbeit einfach später alleine nachzuholen und allenfalls jemanden zu fragen falls ich es nicht verstehe. Auch als die BAIN-Onlinevorlesung zu Ende war funktionierte noch immer nichts bei mir. Zuhause habe ich es weiter versucht und irgendwann um ca. 21.00 Uhr war ich eeeendlich auf der Ubuntu Seite. Aber zu früh gefreut, auch da ging einfach nichts. Die Seite war eingefroren, bevor ich meinen Nutzernamen eingeben konnte und beendete sich dann von alleine, weil von der Maschine zu lange keine Antwort gekommen ist. Und dann gings wieder von vorne los. Ich war über mich selbst erstaunt, dass ich nicht an die Decke gegangen bin, es war alles frustrierend. Irgendwann am selben Abend funktionierte es dann ganz kurz. Ich konnte mich mit meiner Maschine verbinden. Immerhin das war mal geschafft. Nur leider als ich wieder aus der Maschine raus ging, kam ich nicht wieder rein. Irgendwie hassen mich technische Geräte einfach. Der FHGR-Support war zu diesem Zeitpunkt natürlich schon längst benachrichtigt worden. 

Am nächsten Morgen früh meldetet sich Merr Meier aus der FHGR IT, ich musste den VPN Client (Pulse Secure) auf die neuste Version updaten, da mein WLAN nicht funktioniert, wenn ich eine VPN-Verbindung zur FHGR habe. Leider hat das nicht geholfen. Herr Martin Meier, der übrigens mein Held vom Tag ist, hat dann mit dem Teamviewer in meinen Laptop geschaut. Er hat herausgefunden, dass bei mir der Traffic über einen falschen Kanal läuft, wenn die VPN-Verbindung zur FHGR besteht. Im „Hackermodus“ hat er das berichtigt und jetzt läuft alles wie am Schnürchen. Es macht richtig Freude. Das WLAN ist während der Verbindung plötzlich wieder so schnell und ich komme mühelos in die Linux Umgebung und kann da auch Kommandos schreiben ohne Angst zu haben, dass gleich alles wieder zusammenstürzt. An dieser Stelle nochmals einen herzlichen Dank an Martin Meier vom FHGR IT-Support. Wenn jemand von meinen Nachfolgenden das liest: bitte keine Panik. Ich war die einzige, bei der es so lange nicht funktioniert hat und der IT Support sowie Felix Lohmeier und Sebastian Meyer sind sehr hilfsbereit. Meine Empfehlung ist, sich zügig bei der IT bzw. den Dozenten zu melden wenn Verbindungsprobleme oder Ähnliches bestehen. 
Jetzt bin ich bereit mit dem eigentlichen Lernstoff zu beginnen und freue mich darauf mich wieder richtig auf den kommenden Unterricht konzentrieren zu können.


## Was ist sonst noch passiert

Neben dem Einrichten der Unix Umgebung und dem vorstellen haben wir die sehr interessante CodiMD-Umgebung von GWDG kennengelernt. Das kannte ich vorher noch nicht und finde ich sehr spannend, vor allem dass ene Bearbeitung des Textes von jedem möglich ist, der den Link kennt. In einem anderen Kurs (Projektkurs) haben wir (bzw. die Projektleitung) entschieden, die in diesem Modul neu kennengelernte CodiMD-Umgebung als gemeinsame Arbeitsplattform zu verwenden. Schon alleine dafür hat sich der Kurs wohl gelohnt. 

## Grundlagen der Unix Shell

Jetzt doch noch ein bisschen etwas Theoretisches zu den Grundlagen der Unix-Shell. Die Unix-Shell wird benötigt zur Administration von Linuxservern. Die meisten Linuxserver werden nicht mit einer grafischen Oberfläche installiert. Das liegt vor allem daran, weil bei grafischen Oberflächen Sicherheitslücken enthalten sein können. Es dient also zur IT-Sicherheit. Wenn keine grafischen Oberflächen da sind, können auch keine Sicherheitslücken auf der grafischen Oberfläche enthalten sein. Die Unix Shell dient nicht nur zur Systemkonfiguration sondern kann auch zur Automatisierung von kleineren Aufgaben verwendet werden (BAIN-Vorlesung vom 10. September). 

# [Navigating the filesystem](https://librarycarpentry.org/lc-shell/02-navigating-the-filesystem/index.html) 

In der Library Carpentry von der UNIX Shell "Navigating the filesystem" wird gezeigt wie man sich im Dateisystem in der Shell bewegt. Es wird gezeigt wie man Shell Kommandos benutzt um mit Verzeichnisse und Dateien zu arbeiten und um Dateien zu finden und zu verändern. Alles angefangen mit den Basics. 
Schnell habe ich gelernt, dass ich mit dem Kommando *pwd* herausfinden kann wo in den Dateien ich mich gerade befinde. 

<img alt="pwd" src="https://github.com/stemorit/BAIN-Lerntagebuch/blob/master/_posts/Screenshot%202020-09-19%20194517.png?raw=true" width="30%"/>

Weiter habe ich in diesem Tutorial gelernt den Inhalt des Verzeichnises mit "-ls" anzusehen in dem ich mich gerade befinde. Unter anderem habe ich auch mit "cd Desktop" von meinem Home Verzeichnis auf den Desktop gewechselt und "pwd" wieder geschaut ob der Wechsel funktioniert hat.

<img alt="Shell" src="https://github.com/stemorit/BAIN-Lerntagebuch/blob/master/_posts/Screenshot2.png?raw=true" width="50%"/>


Um jetzt aber niemanden viel länger mit dieses Basics zu langweilen, werde ich noch kurz erläutern was im Tutorial von "Working with files and directories" gezeigt wird und freue mich dann, auf weitere spannede Inhalte, welche natürlich im nächsten Blogpost auseinandergenommen werden. Dieser Blogpost wird sonst zu lange, weil die Einstiegshürden so gross waren.

**Edit:** Wichtig anzumerken finde ich noch, dass man mit dem Befehl "q" wieder raus aus den "man" Anleitungen kommt, sonst kann man schnell mal dort verloren sein. Als Bespiel: "man ls" zeigt was der Befehl "ls" macht.
Und hier noch ein Zitat von der Seite: "Knowing where you are in your directory structure is key to working with the shell"

# [Working with files and directories](https://librarycarpentry.org/lc-shell/03-working-with-files-and-folders/index.html)

In der Library Carpentry von der UNIX Shell "Working with files and directories" werden diese Fragen geklärt: Wie kann ich Dateien und Verzeichnisse kopieren, verschieben und löschen? Wie kann ich Dateien lesen?

Diese Shell Kommandos wurden bis jetzt von mir aus beiden Links gelernt und angewendet:

## Shell Kommandos

pwd  --> In welchem Ordner befinde ich mich?

ls --> Inhalt des Verzeichnisses als Liste aufzeigen

ls -l --> Liste vom Inhalt mit mehr Informationen wie die Grösse der Dateien in Bytes, das Erstellungsdatum und den Dateinamen

ls -lh --> selbe Liste wie «ls -l» aber mit Einheiten bei der Grösse der Dateien.

cd Desktop --> Verzeichnis wechseln (Hier zum Desktop)

man (bsp. man ls) --> Beschreibt was das Kommando «ls» macht

q --> quit, damit kommt man aus der «man»-Hilfeansicht

mkdir directory --> Erstellt ein neues Verzeichnis mit dem Namen «directory»

cd .. --> geht im Verzeichnis eine Ebene höher

cat directory.txt --> lesen des Textes der Datei directory.txt

head directory.txt --> lesen des Kopfs der Datei directory.txt erste 10 Linien

head -n 20 directory.txt --> Lesen der ersten 20 Zeilen.

tail directory.txt --> lesen der letzten 10 Zeilen von der Datei directory.txt

mv directory.txt file.txt --> umbenennen von directory.txt zu file.txt

mv file.txt folder --> Dokument file.txt wird in den ordner folder verschoben

cp file.txt file-backup.txt --> kopiert das Dokument file.txt als file-backup.txt

history --> zeigt die letzten eingegebenen Kommandos auf

rm file.txt --> löscht das Dokument file.txt




Offene Fragen oder Probleme gibt es Momentan keine.
