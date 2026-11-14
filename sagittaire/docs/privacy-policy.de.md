# Datenschutzerklärung

*Version 5 · Gültig ab 14. November 2026*

*Dies ist eine Übersetzung, die dir nur zur besseren Verständlichkeit bereitgestellt wird; maßgeblich sind allein die französische und die englische Fassung, die bei jeder Abweichung Vorrang haben.*

Diese Erklärung beschreibt, welche Informationen die Anwendung sagitt·AI·re (die „App“) verarbeitet, wo sie aufbewahrt werden, wann sie dein Gerät verlassen und was du in Bezug auf sie tun kannst. Sie ist Teil der Nutzungsbedingungen. „Entwickler“ bezeichnet Ashencroft Studio — Experten für verantwortungsvolle KI & Hyperautomatisierung, den Entwickler von sagitt·AI·re.

## 1. Kurz gesagt

Der Entwickler erhebt nichts. Die App hat kein Konto, keine Werbung, keine Analyse und kein Tracking, und sie sendet nichts an den Entwickler. Deine Aufzeichnungen bleiben auf deinem Gerät. Ein Foto der Scheibe verlässt dein Gerät nur, wenn du dich dafür entscheidest, eine Passe von einem Dienst der künstlichen Intelligenz („KI“) werten zu lassen, und dann nur an diesen Dienst.

## 2. Was die App auf deinem Gerät speichert

Damit sie funktioniert, speichert die App Folgendes in ihrem privaten Speicher auf deinem Gerät:

- deine Bögen (Name, Typ, Einstellungen und die Beschreibung deiner Pfeile) und die Orte, an denen du schießt, so wie du sie benennst;
- deine Einheiten: Datum, Ort, Bogen, Entfernung, Auflage, Passen, Pfeile, Ergebnisse sowie das Foto jeder Passe mit einer kleinen Vorschau;
- deine Einstellungen, darunter deine Wertungsmethode, die von dir eingerichteten KI-Dienste, ihre Adressen und Modelle, dein Erscheinungsbild und deine Bogenschützenfigur im Spielmodus sowie das Datum, an dem du die Nutzungsbedingungen akzeptiert hast;
- deine API-Schlüssel, verschlüsselt mit einem Schlüssel, der in der sicheren Hardware des Geräts aufbewahrt wird (Android Keystore).

Andere Apps können diese Informationen nicht lesen, und die Fotos erscheinen nicht in deiner Galerie. Die App schaltet die automatische Cloud-Sicherung von Android und die Übertragung von Gerät zu Gerät ab, sodass nichts davon automatisch von deinem Gerät kopiert wird.

## 3. Wann Informationen dein Gerät verlassen

**Wertung mit deinem eigenen API-Schlüssel.** Wenn eine Passe gewertet wird, sendet die App über eine verschlüsselte Verbindung (HTTPS) und nur an den von dir gewählten KI-Dienst, an die mit seinem Schlüssel gespeicherte Adresse:

- das Foto der Passe, aus dem die versteckten Daten (Standort, Gerätemodell, Datum) entfernt wurden und das, sofern du dies nicht abschaltest, auf das Quadrat um den Rahmenkreis zugeschnitten ist, was das meiste der Umgebung weglässt, aber nicht, was vor der Scheibe steht;
- die Angaben, die der Dienst für die Wertung braucht: die Auflage und die Auflagen auf der Scheibe, die Anzahl der Pfeile, die Wertungsregel, deine Pfeilbeschreibung und die Sprache für seine Anmerkungen;
- deinen API-Schlüssel, der dein Konto bei diesem Dienst identifiziert.

Dein Name, deine Orte, dein Verlauf, deine Ergebnisse und Angaben zu deinem Gerät werden nie gesendet. Die technischen Angaben zum Gerät, die Apps üblicherweise senden, werden durch „unknown“ (unbekannt) ersetzt. Wie jeder Internetdienst kann der KI-Dienst deine Netzwerkadresse (IP-Adresse) sehen.

**Teilen mit deiner KI-App.** Die App bereitet das Foto und einen Prompt vor, und du wählst über das Teilen-Menü von Android die App aus, mit der du sie teilst. Was danach geschieht, ist eine Sache zwischen dir und dieser App.

**Manuelle Wertung.** Nichts verlässt dein Gerät.

**Teilen einer Einheit.** Wenn du bei einer Einheit auf Teilen tippst, bereitet die App eine Zusammenfassung vor (Datum, Bogen, Ort, Runde, Ergebnisse und, wenn du möchtest, ein Bild des Schießzettels), und du wählst die App aus, mit der du sie teilst. Die Fotos deiner Passen sind nie enthalten.

**Ein Wertungsproblem melden.** Wenn du bei einer Passe auf „Wertungsproblem melden“ tippst, schreibt die App eine E-Mail zu dieser Passe (Auflage, Entfernung, Regel, KI-Modell und jeder Pfeil so, wie die KI ihn gewertet hat und wie er jetzt ist) und hängt, wenn du es ankreuzt, die Kopie des Fotos an, die an den KI-Dienst geht. Deine E-Mail-App öffnet sich ohne Empfänger: Du wählst, an wen sie geht, und nichts wird gesendet, bevor du sie sendest. Deine Bögen, Orte und Daten sind nicht enthalten.

**Exporte.** Wenn du deine Aufzeichnungen exportierst, schreibt die App eine unverschlüsselte Datei an den Ort, den du wählst (zum Beispiel deinen Download-Ordner oder einen Cloud-Speicher). Je nachdem, was du exportierst, enthält sie deine Bögen, Orte, Einheiten, Passen, Pfeile und Notizen, die Antwort des KI-Dienstes zu jeder Passe, deine Einstellungen außer Schlüsseln und Adressen sowie die Fotos deiner Passen in voller Größe und unbeschnitten, mit allen Personen und Dingen, die darauf zu sehen sind. API-Schlüssel und Dienstadressen werden nie in einen Export aufgenommen. Bewahre die Datei an einem privaten Ort auf und lösche Kopien, die du nicht mehr brauchst: Wer die Datei hat, kann deine Aufzeichnungen lesen und deine Fotos sehen.

**Prüfen eines Schlüssels.** Die Schaltfläche „Schlüssel prüfen“ sendet deinen Schlüssel an den zugehörigen Dienst, um zu bestätigen, dass er funktioniert.

## 4. KI-Dienste

Jeder KI-Dienst, den du nutzt, ist ein eigenständiges Unternehmen mit eigenen Nutzungsbedingungen und eigener Datenschutzerklärung. Diese legen fest, wie er das, was er erhält, verwendet, aufbewahrt und schützt, einschließlich der Frage, ob er es zum Training seiner Modelle verwenden darf und wo auf der Welt er es verarbeitet, was auch außerhalb von Québec und Kanada sein kann. Lies sie, bevor du den Dienst nutzt, und wähle den Dienst und die Einstellungen deines Kontos dort entsprechend. Der Entwickler hat keine Kontrolle über diese Dienste und erhält nichts von ihnen.

Stand November 2026 sagen die Dienste, die die App anbietet, Folgendes über das, was sie über ihre APIs erhalten. Ihre eigenen Bedingungen haben Vorrang und können sich ändern, und die Website von sagitt·AI·re gibt an, was jeder Dienst sagt:

- Sie bewahren es je nach Dienst bis zu 30 oder 55 Tage zur Missbrauchserkennung auf, und manche bis zu 2 Jahre, wenn ihre Sicherheitssysteme es markieren;
- manche prüfen Bilder auf Darstellungen sexuellen Kindesmissbrauchs und bewahren markierte Bilder zur Prüfung auf;
- mit einem kostenpflichtigen Konto verwenden sie es nicht zum Training ihrer Modelle oder zur Verbesserung ihrer Produkte, außer du stimmst dem in deinem Konto zu;
- das kostenlose Angebot eines der Dienste verwendet es zur Verbesserung seiner Produkte, und menschliche Prüfer können es lesen: Verwende bei diesem Dienst einen Schlüssel mit aktivierter Abrechnung, wie es die Einstellungen der App erklären.

## 5. Berechtigungen

- **Kamera**, um die Scheibe zu fotografieren. Android fragt dich beim ersten Mal.
- **Internet**, um den von dir gewählten KI-Dienst zu erreichen. Bei manueller Wertung wird sie nicht genutzt.

Die App fragt nicht nach Berechtigungen für Standort, Kontakte, Mikrofon oder Speicher. Zum Importieren eines Fotos wird die Fotoauswahl von Android verwendet, die der App nur das Foto gibt, das du auswählst.

## 6. Wie lange Informationen aufbewahrt werden

Deine Informationen bleiben auf deinem Gerät, bis du sie löschst. Du kannst eine Passe oder eine Einheit löschen, alte Fotos in voller Größe löschen (Einstellungen → Speicher und Sicherung → Speicher freigeben), einen Schlüssel entfernen oder alle Einheiten oder alles löschen (Einstellungen → Speicher und Sicherung → Daten löschen). Wenn du die App deinstallierst, wird alles gelöscht, was sie auf deinem Gerät speichert.

## 7. Deine Wahlmöglichkeiten und Rechte

Da der Entwickler keine Informationen über dich hat, befindet sich alles, was die App über dich weiß, auf deinem Gerät und unter deiner Kontrolle: Du kannst es in der App einsehen, mit einem Export eine Kopie davon erstellen, es berichtigen und löschen, wie oben beschrieben. Für Informationen, die ein KI-Dienst erhalten hat, nutze die Rechte, die dir dessen Datenschutzerklärung einräumt; nach dem Recht von Québec und Kanada sowie dem Recht deines Wohnorts kannst du gegenüber diesem Dienst Rechte auf Auskunft, Berichtigung und Löschung haben.

## 8. Sicherheit

Die App schützt deine Informationen mit der App-Sandbox von Android, verschlüsselt deine API-Schlüssel, sendet Wertungsanfragen nur über HTTPS, blockiert unverschlüsselte Verbindungen und entfernt versteckte Daten aus Fotos, bevor sie gesendet werden. Keine Methode ist vollkommen sicher: Schütze dein Gerät mit einer Displaysperre, erstelle einen API-Schlüssel nur für die App mit einem Ausgabenlimit und lösche ihn beim zugehörigen Dienst, wenn dein Gerät verloren geht.

## 9. Kinder

Die App richtet sich nicht an Kinder unter 14 Jahren und erhebt von niemandem Informationen. KI-Dienste legen ihr eigenes Mindestalter fest. Ein Elternteil oder eine erziehungsberechtigte Person sollte jeden KI-Dienst einrichten, den ein Kind nutzt, oder die manuelle Wertung wählen, bei der nichts gesendet wird.

## 10. Die Website

Die Website von sagitt·AI·re (ashencroft-hyperautomation.github.io/sagittaire) wird von GitHub gehostet. Wenn du sie besuchst, erhält GitHub deine Netzwerkadresse (IP-Adresse) und die Seiten, die du aufrufst, und verarbeitet sie gemäß der Datenschutzerklärung von GitHub; der Entwickler erhält diese Protokolle nicht. Die Website hat kein Konto, keine Cookies, keine Analyse, keine Werbung und kein Tracking. Ihre Schriften und anderen Dateien kommen von der Website selbst, sodass bei einem Besuch mit einem aktuellen Browser kein anderer Dienst kontaktiert wird. Deine Wahl zwischen hellem und dunklem Erscheinungsbild merkt sich nur dein Browser. Wenn du auf GitHub ein Issue eröffnest, ist das, was du schreibst, öffentlich und wird von GitHub nach seinen eigenen Bedingungen verarbeitet.

## 11. Änderungen dieser Erklärung

Wenn sich diese Erklärung inhaltlich ändert, wird die neue Fassung mit ihrem Datum in der App angezeigt, und du wirst gebeten, die Nutzungsbedingungen erneut zu akzeptieren, bevor du weitermachst. Die aktuelle Fassung ist immer in der App (Einstellungen → Info und Rechtliches) und auf der Website von sagitt·AI·re verfügbar.

## 12. Fragen

Die App und ihre Website werden pro bono für Archery Canada gemacht und vom Entwickler betrieben. Bei Fragen zu dieser Erklärung eröffne ein Issue unter github.com/ashencroft-hyperautomation/ashencroft-hyperautomation.github.io/issues. Issues sind öffentlich: Füge keine personenbezogenen Informationen, Fotos oder API-Schlüssel hinzu.

## 13. Sprache

Diese Erklärung ist in französischer und in englischer Sprache abgefasst; beide Fassungen sind gleichermaßen verbindlich. *Cette politique est rédigée en français et en anglais; les deux versions font également foi.*
