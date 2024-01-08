# 01_Leseauftrag
## Wohin sichern?
Backups sollten auf einem Physischen Laufwerk und/oder auf einer Cloud gespeichert sein, damit bei einem Hausbrand zum Beispiel die Daten immer noch verfügbar sind.
## Datensicherungsstrategien
- **Vollständige Sicherung:**
	Alle ausgewählten Daten werden gesichert
- **Inkrementelle Sicherung:**
	Lediglich die seit der letzten Sicherung veränderten oder neu hinzugefügten Daten werden gesichert.
- **Differentielle Sicherung:**
	Es werden ausschließlich die Daten gesichert, die sich seit der letzten vollständigen Sicherung verändert haben.
## Schnittstellen
- **Physische Schnittstellen (USB, SATA):**
     Direkte Verbindung von Speichermedien zur Sicherung der Daten.
-  **Netzwerkschnittstellen (LAN, WLAN):**
	Sicherung über das Netzwerk auf entfernte Speicherorte oder Server.
- **Cloud-Schnittstellen:**
	Verwendung von Cloud-Diensten zur Durchführung der Datensicherung.
# 02_Backupkonzept

| Service        | Funktion           | Betroffene Daten                                   | Backup                                              | Wiederherstellung                                      |
| -------------- | ------------------ | -------------------------------------------------- | ---------------------------------------------------- | ------------------------------------------------------- |
| WhatsApp       | Nachrichten         | Chatverläufe (Text, Fotos, Videos, Ton) mit Kontakten | Sicherung in Google Drive mit Passwortschutz (in App-Einstellungen) | Daten werden während der Neuinstallation abgefragt     |
| Fotos-App      | Fotos              | Persönliche Fotos und Alben                         | Automatische Sicherung in Google Fotos                | Fotos-App erneut installieren und Google Fotos öffnen |
| Kontakte       | Kontaktdaten        | Telefonnummern, Adressen                           | Synchronisation mit Google-Konto                      | Bei erneuter Anmeldung auf dem neuen Gerät              |
| Kalender       | Termine             | Geplante Termine und Ereignisse                    | Synchronisation mit Google-Konto                      | Bei erneuter Anmeldung auf dem neuen Gerät              |
| Notizen-App    | Notizen             | Persönliche Notizen                                | Synchronisation mit einem Cloud-Dienst (z. B. Evernote) | App auf neuem Gerät installieren und einloggen         |
# 03 - Backupkonzept: Datensicherung nach Verlust des persönlichen Smartphones

| Service        | Funktion           | Betroffene Daten                                   | Backup                                              | Wiederherstellung                                      |
| -------------- | ------------------ | -------------------------------------------------- | ---------------------------------------------------- | ------------------------------------------------------- |
| WhatsApp       | Nachrichten         | Chatverläufe (Text, Foto, Video, Ton) mit Kontakten | Google Drive Backup mit Passwortschutz (App-Konfig.) | Daten werden während der Neuinstallation abgefragt     |
| Fotos-App      | Fotos              | Persönliche Fotos und Alben                         | Automatische Sicherung in Google Fotos                | Fotos-App erneut installieren und Google Fotos öffnen |
| Kontakte       | Kontaktdaten        | Telefonnummern, Adressen                           | Synchronisation mit Google-Konto                      | Bei erneuter Anmeldung auf dem neuen Gerät              |
| Kalender       | Termine             | Geplante Termine und Ereignisse                    | Synchronisation mit Google-Konto                      | Bei erneuter Anmeldung auf dem neuen Gerät              |
| Notizen-App    | Notizen             | Persönliche Notizen                                | Synchronisation mit Cloud-Dienst (z. B. Evernote)     | App auf neuem Gerät installieren und einloggen         |

# 05 - Sicheres Cloud-Backup: 

## Betrachtung der Speicheroptionen

Bei der Wahl einer Backup-Strategie sind verschiedene Faktoren zu berücksichtigen, insbesondere die Vor- und Nachteile von Cloud- und lokalen Speicheroptionen. Hier sind einige Überlegungen:

### Cloud-Speicheroptionen:

**Vorteile:**
	Immer erreichbar: Über das Internet von verschiedenen Geräten aus zugänglich.
	Keine Hardware erforderlich: Kein physischer Speicherplatz notwendig.
	Geräteübergreifende Verfügbarkeit: Über alle gängigen Gerätetypen hinweg zugänglich.
	Zusätzliche Funktionen: Dateien teilen, kollaborativ arbeiten, etc.

**Nachteile:**
	Regelmäßige Kosten: Bei einer gewissen Datenmenge entstehen möglicherweise regelmäßige Kosten.
	Datenschutzbedenken: Abhängig vom Standort des Cloud-Servers und Zugriffsmöglichkeiten.
	Abhängigkeit von externer Firma: Kein physischer Zugriff zu den Daten; Abhängigkeit vom Cloud-Anbieter.
	Internetabhängigkeit: Funktioniert nur bei bestehender Internetverbindung.
	Probleme beim Cloud-Anbieter: Potenzielle Risiken wie Datenlecks oder Verlust von Daten.

### Lokale Speicheroptionen:

**Vorteile:**

Einmalige Kosten: Einmalige Anschaffungskosten für die Hardware.
Physischer Zugriff: Direkter Zugriff auf die Daten über lokale Geräte.
Unabhängig vom Internet: Funktioniert auch ohne Internetverbindung.
Geringere Datenschutzbedenken: Daten verbleiben physisch in Ihrer Kontrolle.

**Nachteile:**
	Begrenzter Zugriff: Lokal gespeicherte Daten sind nicht von überall aus zugänglich.
	Begrenzte Kollaboration: Eingeschränkte Möglichkeiten zur kollaborativen Arbeit.
	Risiko von Hardwarefehlern: Daten können bei Hardwareausfällen gefährdet sein.

## Plurale Backup-Strategie

Angesichts dieser Überlegungen empfiehlt es sich, eine "plurale" Backup-Strategie zu verfolgen, die sowohl lokale als auch Cloud-Sicherungsoptionen umfasst. Dies kombiniert die Vorteile beider Ansätze und bietet Redundanz für verbesserte Datensicherheit.

## Auswahl und Einrichtung eines Backup-Tools

### Tools für Cloud-Backups

Für Cloud-Backups stehen bekannte Open-Source-Tools wie Duplicati und Duplicacy zur Verfügung.

**Anforderungen:**
	Wählen Sie ein Tool, das Ihren Anforderungen entspricht, z. B. Unterstützung für Ihren bevorzugten Cloudspeicher (z. B. Google Drive).

**Vorbereitung:**
	Informieren Sie sich über das ausgewählte Tool und suchen Sie eine Bedienungsanleitung auf der Webseite.

**Ziel setzen:**
	Definieren Sie klare Ziele für Ihr Backup, z. B. "Den Ordner 'TBZ' auf meinem Laptop in meinem privaten Google Drive Account sichern".

**Plan erstellen:**
	Entwickeln Sie einen schrittweisen Plan, wie Sie Ihr Ziel erreichen können.