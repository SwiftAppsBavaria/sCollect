# Hilfe zu sCollect

## Was die App tut

sCollect verwaltet Mediensammlungen — Musik, Filme, Heimvideos, Hörbücher, Podcasts,
E-Books — und Sammlerstücke, die keine Mediendateien sind, etwa Münzen oder Briefmarken.
Wie die Kategorien heißen, bestimmst du unter **Einstellungen → Kategoriebezeichner**
selbst.

Was du im Editor eingibst, schreibt die App **in die Datei zurück**, nicht nur in ihren
eigenen Katalog.

## Erste Schritte

1. Beim ersten Start einen Ordner für die Mediathek wählen. Dort liegen später die
   Katalogdaten und, wenn du es so möchtest, auch die Mediendateien.
2. Dateien oder Ordner über **Ablage → Dateien importieren** (⌘O) oder **Ablage → Ordner importieren** (⇧⌘O) hereinholen oder auf das Fenster
   ziehen.
3. Beim Import entscheidest du je Lauf, ob die Dateien **in die Mediathek kopiert** oder nur
   **verknüpft** werden.

## Verwaltet oder verknüpft?

| | |
|---|---|
| **Verwaltet** | Die Datei liegt in der Mediathek. sCollect sortiert sie ein, benennt sie nach deinem Schema und schreibt die Tags. |
| **Verknüpft** | Die Datei bleibt, wo sie ist. sCollect merkt sich den Ort und **fasst die Datei nicht an**. |

Die Spalte „Verknüpft“ in der Liste zeigt, was vorliegt.

## Häufige Fragen

**Ein Eintrag hat ein orangefarbenes Warndreieck.**
Seine Datei war beim letzten Durchlauf von **Ablage → Mediathek → Fehlende markieren** nicht
auffindbar. Der Eintrag lässt sich dann nicht bearbeiten — es gibt nichts, wohin geschrieben
werden könnte. Über das Kontextmenü bietet die App **Datei suchen…** an; die gefundene Datei
wird in die Mediathek zurückgeholt.

**Im Kontextmenü steht „Laufwerk nicht angeschlossen“, abgeblendet.**
Dann ist nicht die Datei weg, sondern die Platte. sCollect unterscheidet die beiden Fälle
ausdrücklich: Was nicht angeschlossen ist, kann es auch nicht prüfen — und markiert es
deshalb auch nicht als fehlend. Schließ die Platte an und lass den Durchlauf erneut laufen.

**Ein Medientyp ist grau und lässt sich nicht ändern.**
Sein Ordner ist gerade nicht erreichbar. sCollect sperrt solche Typen, statt die Dateien
stillschweigend woanders abzulegen. Sobald die Platte wieder da ist, ist die Sperre vorbei.

**Der Editor zeigt „Ein Feld weicht von der Datei ab“.**
Die Datei trägt in einem Feld etwas anderes als die Mediathek — meist, weil ein anderes
Programm sie zwischenzeitlich bearbeitet hat. Der Streifen über den Feldern zeigt, welche
betroffen sind, und du entscheidest je Feld, ob der Wert aus der Datei übernommen wird.

**Ich finde ein Feld nicht, das ich brauche.**
Für Sammlerstücke gibt es drei frei benennbare Felder. Wie sie heißen sollen, stellst du je
Kategorie unter **Einstellungen → Feldbezeichner** ein.

**Kann ich meine iTunes- oder Musik-Sammlung übernehmen?**
Ja. sCollect liest die iTunes-XML samt Bewertungen und Playlisten. Die Titel werden
dabei über ihre Dateipfade zugeordnet; vorhandene Bewertungen werden nicht überschrieben.

**Wie bekomme ich meine Sammlung wieder heraus?**
Über die **sCollect-XML** — sie ist verlustfrei und dient zugleich als Sicherung. Daneben gibt
es den Export als iTunes-XML und als Playlist für Apple Music.

**Was macht die Synchronisation mit Kopien?**
Eine Mediathek kann andere Mediatheken als Kopien anmelden. Änderungen am Hauptbestand werden
dorthin nachgezogen, Dateien und Tags eingeschlossen. Ist eine Kopie gerade offline, bleibt
die Änderung liegen und wird nachgeholt.

⚠️ **Das ist kein Backup.** Eine gelöschte Datei wird auch in den Kopien gelöscht — das ist
der Zweck einer Synchronisation. Für den Fall, dass etwas schiefgeht, brauchst du zusätzlich
eine echte Sicherung.

**Verliert meine Datei beim Tag-Schreiben an Qualität?**
Nein. Die Audio- und Bilddaten werden unverändert übernommen; es wird nichts neu kodiert.
Wo es geht, ändert sCollect nur die wenigen Bytes des Tags, statt die Datei neu zu schreiben.

**Brauche ich eine Sicherung?**
Ja. sCollect schreibt in deine Dateien, nicht in eine Kopie davon. Lege vor großen Änderungen an vielen Einträgen auf einmal eine Sicherung an; Time Machine genügt.

**Kann ich eine Änderung widerrufen?**
Gelöschte Einträge holt ⌘Z zurück. Änderungen an Metadaten nicht — lege deshalb vor einem
großen Stapellauf eine Sicherung an.

## Etwas geht schief?

sCollect schreibt ein Protokoll in den Ordner deiner Mediathek — es hält fest, was die App
wann getan hat. Schick es gern mit der Fehlerbeschreibung mit.

## Kontakt

SwiftAppsBavaria · SwiftAppsBavaria@gmx.net
