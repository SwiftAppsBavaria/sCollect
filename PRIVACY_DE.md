# Datenschutzerklärung für sCollect

Stand: 2026-11-16

## Kurzfassung

sCollect erhebt, speichert und übermittelt **keine** personenbezogenen Daten. Die App
arbeitet ausschließlich auf deinem Mac bzw. Windows-PC. Es gibt keine Konten, keine Cloud-Anbindung, keine
Analysedienste und keine Werbung.

## Welche Daten die App verarbeitet

sCollect liest und schreibt die Mediendateien in den Ordnern, die du ihm ausdrücklich
übergeben hast — durch Auswahl im Öffnen-Dialog oder durch Ziehen auf das Fenster. Gelesen
werden Dateiname, Dateigröße, Datum und die Metadaten der Datei; geschrieben werden die
Angaben, die du im Editor eingibst.

Ohne deine Auswahl greift die App auf keine Datei zu. macOS setzt das über die App-Sandbox
durch.

## Was die App auf deinem Mac ablegt

- **Die Mediathek selbst** im Ordner, den du dafür gewählt hast: die Katalogdaten, die
  Titelbilder und ein Protokoll der noch nicht ausgeführten Abgleiche.
- **Einstellungen und Fensterlagen** im geschützten App-Ordner der App.
- **Die Erlaubnis von macOS, deine Ordner beim nächsten Start wieder zu öffnen.** Gespeichert
  werden Ordnerpfade, keine Dateiinhalte. Nur so muss die App nicht bei jedem Start erneut
  fragen.
- **Ein Diagnoseprotokoll** mit Zeitpunkten und Anzahlen von Vorgängen. Es bleibt auf deinem
  Mac; du kannst es sichern und weitergeben, wenn du einen Fehler meldest.

Alles davon wird entfernt, wenn du die App und ihre Mediathek löschst.

## Zwei Berechtigungen, die Fragen aufwerfen können

**Netzwerkzugriff.** Die App fordert ihn an, weil macOS das eingebaute Hilfe-Fenster ohne
diese Berechtigung leer anzeigt — die Hilfe wird von einer Systemkomponente dargestellt, die
sie benötigt, auch wenn sie nur Dateien aus dem Programm selbst lädt. sCollect ruft von sich
aus **keine Adresse im Internet auf**, lädt nichts nach und meldet nichts.

Mediatheken auf Netzlaufwerken (SMB, NFS) erreicht die App über das Dateisystem deines Macs,
nicht über eine eigene Verbindung.

**Steuerung von Apple Music.** Beim Ausspielen einer Playlist öffnet sCollect
Apple Music mit der erzeugten Datei. Dafür verlangt macOS deine Zustimmung, und sie wird beim
ersten Mal abgefragt. Andere Programme steuert die App nicht.

## Deine Dateien

sCollect verändert die Metadaten in genau den Dateien, die zu deiner Mediathek gehören, und
verschiebt sie beim Einsortieren innerhalb der Ordner, die du freigegeben hast.

**Verknüpfte Objekte bleiben unangetastet** — sie liegen außerhalb der Mediathek, und die App
schreibt dort nichts hinein.

Gelöschte Dateien wandern zunächst in einen eigenen Papierkorb innerhalb der Mediathek und
lassen sich von dort zurückholen. Endgültig entfernt werden sie erst, wenn du ihn leerst.

## Unter Windows

Die Abschnitte oben beschreiben den Mac. Unter Windows legt sCollect Folgendes ausschließlich lokal ab:

Im Datenordner der App (`%LOCALAPPDATA%\Packages\<Paket>\LocalState` und `Settings`):

- **Einstellungen, Fensterlage und Ansicht** — zuletzt geöffnete Mediatheken, die Auswahl in der Seitenleiste, die zuletzt
  gespielten Titel, Spalten und Sortierung.
- **Die Zuordnung der Mac-Ordner einer Mediathek zu Ordnern auf deinem PC** (nur Ordnerpfade).
- **Eingabehilfen** — Werte, die du in Feldern wie Genre oder Sprache schon benutzt hast, als Vorschläge.
- **Eine zufällige Kennung dieses PCs.** Sie unterscheidet deine Rechner bei Kopien einer Mediathek und enthält nichts über dich.
- **Ein Diagnoseprotokoll** mit Zeitpunkten, Vorgängen und den betroffenen Dateipfaden, und ein **Fehlerprotokoll**
  (`fehler.log`, sieben Tage). Beide bleiben auf deinem PC; du kannst sie weitergeben, wenn du einen Fehler meldest.

Im Ordner der Mediathek, den du gewählt hast: die Katalogdaten, Titelbilder, der Papierkorb der Mediathek und — wenn sie Kopien hat — deren Orte
und die noch nicht ausgeführten Abgleiche. Solange sCollect eine Mediathek geöffnet hat, liegt dort außerdem eine **Sperrdatei** mit dem
**Namen deines PCs**, damit nicht zwei Rechner gleichzeitig in dieselbe Mediathek schreiben. Liegt die Mediathek auf einem
Netzlaufwerk, können andere Nutzer dieses Laufwerks den Namen sehen.

Was im Datenordner der App liegt, wird entfernt, wenn du die App deinstallierst; die Mediathek bleibt, bis du sie selbst löschst.

sCollect liest und schreibt Mediendateien nur in den Ordnern, die du ihm gibst. Die App baut keine eigenen Netzverbindungen auf,
nutzt keine Analysedienste und zeigt keine Werbung. Dateien, die Windows nicht selbst abspielt, übergibt sie an das
Standardprogramm für den Dateityp — welches das ist, stellst du in Windows ein. Zum Umwandeln und Kürzen von Ton und Film nutzt sie
das beigelegte FFmpeg, ebenfalls nur auf deinem PC.

Sendest du eine Playlist an iTunes, öffnet sCollect iTunes für Windows mit dieser Playlist; andere Programme steuert die App nicht.
Exportierst du eine Playlist für VLC oder ein Gerät, kopiert die App deren Dateien in den Ordner, den du wählst.

## Microsoft Store

Unter Windows laufen Kauf, Download und Updates über den Microsoft Store; dafür gilt die Datenschutzerklärung von Microsoft.

## Keine Weitergabe, keine Analyse

Es gibt keine Werbung, keine Analysedienste, keine Absturzberichte an Dritte und keine
Konten.

## Kontakt

Andreas Heiligtag · SwiftAppsBavaria@gmx.net
