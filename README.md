Mit dem Bash-Script können die Daten auf einer CAN-Schnittstelle in einem Logfile gesichert und dabei ggf. aktiv beobachtet werden.
Dazu muss vorab eine entsprechende Schnittstelle 
(z.B. can0) konfiguriert sein.
In meinem Fall habe ich einen entsprechenden Hat auf einem Raspberry genutzt.
[Die Funktion wurde mit "RS485 CAN HAT" von Waveshare und mit dem "RS485&CAN Module" von inno-Maker getestet].

Installation:
nach dem download kann die Datei "canmoni"
in "/usr/bin/" kopiert und mit sudo "chmod 755 /usr/bin/canmoni" ausführbar gemacht werden.
So kann durch Eingabe von canmoni das Script gestartet werden.
Die Logdatei wird im aktuellen Verzeichnis mit YYYY-MM-DD_HH-MM-SS.txt erzeugt.