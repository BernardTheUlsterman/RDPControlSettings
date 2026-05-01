# RDP Control Settings

Die Einstellungen für die RDP-Verbindungen befinden sich unter dem Hauptmenü (<b>Main Menu</b>).

Erweitern Sie das Hauptmenü unter <b> Main Menu </b> - <b> RDP Control </b> und wählen Sie <b> Settings </b>, um die Einstellungen der RDP-Verbindung zu konfigurieren. 

<img width="1257" height="748" alt="image" src="https://github.com/user-attachments/assets/dd023a53-f914-4f2c-ab84-d74f11a8e70c" />

Sie können hier mehrere Profile mit verschiedenen Einstellungen anlegen. Sie haben hier die folgenden Optionen:

<img align="left" width="20" height="20" alt="image" src="https://github.com/user-attachments/assets/14818edc-38f2-4855-a38f-942665163539" /> Wählen Sie diese Schaltfläche, um eine neues Profil für Ihre RDP-Verbindungen zu erstellen. Im roten Feld geben Sie diesem Profil einen Namen.

<img align="left" width="20" height="20" alt="image" src="https://github.com/user-attachments/assets/063beb9d-b2e3-43fd-b6dc-40636561f96f" /> Mit dieser Schaltfläche können Sie die Einstellungen des gewählten Profils einblenden.

<img align="left" width="20" height="20" alt="image" src="https://github.com/user-attachments/assets/db082367-08cf-42e4-b635-330e037fc0df" /> Mit dieser Schaltfläche können Sie die Einstellungen des gewählten Profils ausblenden.

<img align="left" width="20" height="20" alt="image" src="https://github.com/user-attachments/assets/2ef0f896-2dc1-42af-b480-947dadda2ac3" /> Mit dieser Schaltfläche können Sie das gewählte Profil entfernen.

Für die RDP-Verbindung können Sie in jedem Profil die folgenden Parameter definieren:

- <b> Idle timeout </b> <br>
Hier sollte ein hoher Wert gewählt werden, um die Verbindung nicht vorzeitig abbrechen zu lassen. Vorgegeben sind 600.000 ms (entsprechend 10 min).

- <b> Maximum display width </b> <br>
Maximale Anzeigebreite des Remote Desktops  in Pixel (px). Dieser Wert sollte anhand der gewünschten Auflösung und der Auflösung des vorhandenen Monitors gewählt werden. Vorgegeben sind 2000 px. 

- <b> Maximum display height </b> <br>
Maximale Anzeigehöhe des Remote Desktops in Pixel (px). Dieser Wert sollte anhand der gewünschten Auflösung und der Auflösung des vorhandenen Monitors gewählt werden. Vorgegeben sind 2000 px. <br> <br> <b> Hinweis: </b> Wenn Sie die RDP Option Use all my monitors for the remote session verwenden, um mehrere Monitore für den Remote Desktop zu verwenden, beachten Sie bitte, maximale Breite und Höhe der Anzeige entsprechend gross zu dimensionieren damit die Auflösungen aller verwendeten Monitore miteingeschlossen sind.

- <b> Maximum display depth </b> <br>
Maximale Farbtiefe in bpp, dieser Wert kann anhand der gewünschten Farbauflösung eingestellt werden.    Werte  für den Remote Desktop sind 15/16 bpp (High Color), 24 bpp (True Color) oder 32 bpp (Deep Color).

- <b> Enable RDP 4 </b> <br>
Wählen Sie diese Option, um Verbindungen mit RDP Version 4 zu ermöglichen.

- <b> Enable RDP 5 </b> <br>
Wählen Sie diese Option, um Verbindungen mit RDP Version 5 zu ermöglichen.

- <b> Enable RDP 6 or newer </b> <br>
Wählen Sie diese Option, um Verbindungen mit RDP ab Version 6  zu ermöglichen.

- <b> Enable RDP 4-style authentication </b> <br>
Bei Kompatibilitätsproblemen mit RDP ab Version 5 können Sie diese Option wählen um die Authentifizierung wie in RDP 4 durchzuführen.

- <b> Enable pre channel check </b> <br>
Vor Herstellung der Verbindung wird geprüft, ob die Verbindung zulässig ist oder ob ihr eine Richtlinie entgegensteht. Wenn die Verbindung nicht zulässig ist, wird sie nicht aufgebaut.

- <b> Enable compression </b> <br>
Um die Last auf dem Netzwerk zu begrenzen kann hier die Komprimierung der übertragenen Daten gewählt werden. Ohne Komprimierung kann die Last auf dem Netzwerk bis zu 500% mehr betragen.

- <b> Autologon domain suffix </b> <br>
Für die Verwendung der Autologon-Funktion in Verbindung mit Network Level Authentication  kann hier ein Domain Suffix eingegeben werden. Vorgegeben ist hier der Wert  -AUTO

Nachdem Sie die Einstellungen vorgenommen haben, wählen Sie <b> Commit </b>, um diese zu bestätigen. Anschliessend können Sie dieses Profil in Ihren RDP-Verbindungen auswählen.



