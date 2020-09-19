---
title: "1 Technische Grundlagen "
date: 2020-09-10
---


**Einstiegshürden**

Der Einstieg in das Fach BAIN war hart für mich. Nicht weil ich vom Fach überhaupt nichts verstehe, sondern weil einfach diese Software wieder nicht funktioniert hat. Für das Einrichten der Arbeitsumgebung Linux wurden 20 Minuten eingeplant, für mich waren es eher 20 Stunden. Schon bevor das Fach am 10. September 2020 gestartet ist, hatte ich so eine Ahnung, dass wir die Virtuelle Maschine wieder brauchen werden. Schon im Modul ARIS (oder wars ein anderes Modul?) haben wir sie gebraucht. Bereits damals war die Installation extrem mühsam, daran hatte ich wirklich nur schlechte Erinnerungen. Mittlerweile muss man sich die virtuelle Maschine nicht mehr selbst herunterladen, sondern kann sich einfach mit dem Horizon Client einloggen. Da steht schon alles bereit, was ich sehr gut finde! Leider hat aber auch das bei mir nicht funktioniert. Die Verbindung mit dem Horizon Client wollte einfach nicht funktionieren. Am Tag davor hat es interessanterweise noch funktioniert, aber da habe ich mich im FHGR Gebäude befunden, was wie sich herausstelle auch der Grund war wieso es da noch funktioniert hat. 

Der Unterricht ging schon längst weiter und ich hatte immer noch keine Verbindung. Wir hätten eine Gruppenarbeit machen sollen mit der Unix Shell, aber ich musste mich mit dem Verbinden beschäftigen und habe das leider verpasst. Ich habe dann für mich selbst bestimmt, die Gruppenarbeit einfach später alleine nachzuholen und allenfalls jemanden zu fragen falls ich es nicht verstehe. Auch als die BAIN-Onlinevorlesung zu Ende war funktionierte noch immer nichts bei mir. Zuhause habe ich es weiter versucht und irgendwann um ca. 21.00 Uhr war ich eeeendlich auf der Ubuntu Seite. Aber zu früh gefreut, auch da ging einfach nichts. Die Seite war eingefroren, bevor ich meinen Nutzernamen eingeben konnte und beendete sich dann von alleine, weil zu lange keine Antwort gekommen ist. Und dann gings wieder von vorne los. Ich war über mich selbst erstaunt, dass ich nicht an die Decke gegangen bin, es war alles so frustrierend. Irgendwann am selben Abend funktionierte es dann ganz kurz. Ich konnte mich mit meiner Maschine verbinden. Immerhin das war mal geschafft. Nur leider als ich wieder aus der Maschine raus ging, kam ich nicht wieder rein. Irgendwie hassen mich technische Geräte einfach. Der FHGR-Support war zu diesem Zeitpunkt natürlich schon längst benachrichtigt worden. 

Am nächsten Morgen früh meldetet sich Merr Meier aus der FHGR IT, ich musste den VPN Client (Pulse Secure) auf die neuste Version updaten, da mein WLAN nicht funktioniert, wenn ich eine VPN-Verbindung zur FHGR habe. Leider hat das nicht geholfen. Herr Martin Meier, der übrigens mein Held vom Tag ist, hat dann mit dem Teamviewer in meinen Laptop geschaut. Er hat herausgefunden, dass bei mir der Traffic über einen falschen Kanal läuft, wenn die VPN-Verbindung zur FHGR besteht. Im „Hackermodus“ hat er das berichtigt und jetzt läuft alles wie am Schnürchen. Es macht richtig Freude. Das WLAN ist plötzlich so schnell und ich komme mühelos in die Linux Umgebung und kann da auch Kommandos schreiben ohne Angst zu haben, dass gleich alles wieder zusammenstürzt. An dieser Stelle nochmals einen herzlichen Dank an Martin Meier vom FHGR IT-Support. Wenn jemand von meinen Nachfolgenden das liest: bitte keine Panik. Ich war die einzige, bei der es so lange nicht funktioniert hat und der IT Support sowie Felix Lohmeier und Sebastian Meyer sind sehr hilfsbereit. Meine Empfehlung ist, sich zügig bei der IT bzw. den Dozenten zu melden wenn Verbindungsprobleme oder Ähnliches bestehen. 
Jetzt bin ich bereit mit dem eigentlichen Lernstoff zu beginnen und freue mich darauf mich wieder richtig auf den kommenden Unterricht konzentrieren zu können.


**Ja was ist sonst noch passiert**

Neben dem Einrichten der Unix Umgebung und dem vorstellen haben wir die sehr interessante CodiMD-Umgebung von GWDG kennengelernt. Das kannte ich vorher noch nicht und finde ich sehr spannend, vor allem für die Arbeit in Gruppen. In einem anderen Kurs (Projektkurs) haben wir (bzw. die Projektleitung) entschieden, die neu kennengelernte CodiMD-Umgebung als gemeinsame Arbeitsplattform zu verwenden. Schon alleine dafür hat sich der Kurs gelohnt. 

**Grundlagen der Unix Shell**

Die Unix-Shell wird benötigt zur administration von Linux Servern. Die meisten Linuxserver werden nicht mit einer grafischen Oberfläche installiert. Das liegt vor allem daran, weil bei grafischen Oberflächen Sicherheitslücken enthalten sein können. Es dient also zur IT-Sicherheit. Wenn kiene grafischen Oberflächen da sind können auch keine Sicherheitslücken auf der grafischen Oberfläche enthalten sein. Die Unix Shell dient nicht nur zur Systemkonfiguration sondern kann auch zur Automatisierung von kleineren Aufgaben verwendet werden. 


[Navigating the filesystem](https://librarycarpentry.org/lc-shell/02-navigating-the-filesystem/index.html) 


[Workin with files and directories](https://librarycarpentry.org/lc-shell/03-working-with-files-and-folders/index.html)
