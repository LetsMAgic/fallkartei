# Häufige Fragen – Die Fallkartei

Hier findest du Antworten auf häufige Fragen zur Nutzung, Speicherung, Installation und Funktionsweise von **Die Fallkartei**.

> **Direkt zur App:** https://letsmagic.github.io/fallkartei/

---

## Allgemein

### Was ist Die Fallkartei?

**Die Fallkartei** ist ein inoffizieller Hörspiel-Tracker für **Die drei ???**.

Neben dem klassischen Markieren und Bewerten von Folgen bietet die App unter anderem persönliche Empfehlungen, Smart Playlists, einen Hörverlauf, Statistiken, Favoriten, eine „Als Nächstes“-Liste und redaktionell gepflegte Zusammenhänge zwischen Folgen.

### Ist Die Fallkartei offiziell?

Nein. Die Fallkartei ist ein **inoffizielles, nicht-kommerzielles Fanprojekt** und steht in keiner Verbindung zu Sony Music Entertainment, EUROPA, dem KOSMOS Verlag oder anderen beteiligten Rechteinhabern.

„Die drei ???“, zugehörige Marken, Titel, Cover, Illustrationen und andere geschützte Inhalte gehören den jeweiligen Rechteinhabern.

### Ist die App kostenlos?

Ja. Die Fallkartei ist **kostenlos und werbefrei**.

Es gibt keine kostenpflichtigen Funktionen, Abonnements oder In-App-Käufe.

### Brauche ich einen Account?

Nein.

Die App besitzt weder ein Benutzerkonto-System noch ein eigenes Backend. Deine persönlichen Daten werden lokal auf deinem Gerät gespeichert.

### Auf welchen Geräten funktioniert Die Fallkartei?

Die Fallkartei läuft in modernen Browsern und kann als **Progressive Web App (PWA)** installiert werden.

Unterstützt werden insbesondere:

- iPhone und iPad
- Android
- Desktop-Browser unter Windows, macOS und anderen modernen Systemen

---

## Installation & Updates

### Muss ich Die Fallkartei aus dem App Store oder Play Store laden?

Nein.

Die Fallkartei ist eine **PWA** und wird direkt über die Website installiert:

https://letsmagic.github.io/fallkartei/

Die App erkennt unterstützte Geräte und zeigt eine passende Installationsanleitung an.

### Muss ich die App installieren?

Nein.

Die Fallkartei kann auch ganz normal im Browser verwendet werden. Die Installation auf dem Home-Bildschirm ist freiwillig.

### Wie bekomme ich Updates?

Updates werden über die Web-App und den Service Worker verteilt.

Wenn eine neue Version erkannt wird, zeigt Die Fallkartei einen Hinweis **„Eine neue Version ist verfügbar“** mit der Schaltfläche **„Jetzt aktualisieren“** an.

Deine lokal gespeicherten Bewertungen, Playlists und Hörvorgänge bleiben dabei erhalten.

Falls eine Änderung nach einem Update noch nicht sichtbar ist, hilft es insbesondere auf iPhone und iPad häufig, die installierte PWA einmal vollständig zu schließen und erneut zu öffnen.

---

## Daten & Datenschutz

### Wo werden meine Bewertungen, Playlists und Hörvorgänge gespeichert?

Persönliche Daten werden lokal im Browser beziehungsweise innerhalb der installierten PWA gespeichert.

Dazu gehören unter anderem:

- Hörstatus
- Bewertungen
- persönliche Notizen
- Hörverlauf
- Playlists
- „Als Nächstes“
- Favoriten
- Einstellungen
- Empfehlungsdaten

Die App verwendet dafür hauptsächlich **IndexedDB**.

### Werden meine persönlichen Tracking-Daten an einen Server übertragen?

Die Fallkartei besitzt kein eigenes Backend und überträgt deine persönlichen Bewertungen, Notizen, Playlists oder deinen Hörverlauf nicht an einen eigenen Fallkartei-Server.

Für das Hosting über GitHub Pages, Metadaten- und Coverabrufe sowie beim bewussten Öffnen externer Dienste entstehen jedoch technische Verbindungen zu Drittanbietern. Dabei können insbesondere IP-Adresse und übliche Verbindungsdaten verarbeitet werden.

Weitere Informationen stehen in [PRIVACY.md](./PRIVACY.md).

### Was passiert, wenn ich Browserdaten lösche oder die App entferne?

Da die persönlichen Daten lokal gespeichert werden, können sie beim Löschen von Website-Daten, beim Zurücksetzen des Browsers oder unter bestimmten Umständen beim Entfernen der App verloren gehen.

Deshalb empfiehlt sich regelmäßig ein Backup.

### Kann ich meine Daten sichern?

Ja.

Über die Backup-Funktion kann eine **JSON-Datei** mit deinen persönlichen Daten exportiert werden. Diese Datei kann später wieder importiert werden.

### Kann ich meine Daten auf ein neues Handy übertragen?

Ja.

Dazu auf dem alten Gerät ein Backup exportieren und dieses anschließend auf dem neuen Gerät in Die Fallkartei importieren.

### Werden meine Daten automatisch zwischen mehreren Geräten synchronisiert?

Nein.

Es gibt derzeit keine Cloud-Synchronisation. Jedes Gerät besitzt zunächst seinen eigenen lokalen Datenbestand.

Für einen Gerätewechsel oder das Übertragen des aktuellen Stands dient die Export-/Import-Funktion.

---

## Offline-Nutzung

### Funktioniert Die Fallkartei komplett offline?

Nicht vollständig.

Nach dem ersten Laden sind die Oberfläche, der Grundkatalog und die persönlichen Tracking-Daten **weitgehend offline nutzbar**.

Eine Internetverbindung wird unter anderem benötigt für:

- das Nachladen oder Aktualisieren von Covern
- aktualisierte Online-Metadaten
- das Öffnen externer Streamingdienste
- das Laden einer neuen App-Version

Die Kernfunktionen zum Tracken, Bewerten und Verwalten deiner lokal vorhandenen Daten funktionieren auch ohne dauerhafte Internetverbindung.

---

## Empfehlungen & Algorithmus

### Wie funktioniert der Empfehlungsalgorithmus?

Die Fallkartei besitzt einen eigenen **lokalen Empfehlungsalgorithmus**.

Er berücksichtigt unter anderem deine bisherigen Bewertungen, deinen Hörstatus und weitere Eigenschaften der Folgen. Daraus werden passende Kandidaten gewichtet und als persönliche Empfehlungen vorgeschlagen.

Zusätzlich kannst du die Auswahl mit Filtern einschränken.

### Ist der Empfehlungsalgorithmus eine KI?

Nein.

Die Empfehlungen werden nicht von einem generativen KI-Modell erzeugt. Die App verwendet einen lokal ausgeführten, regel- und gewichtungsbasierten Empfehlungsalgorithmus.

### Woher kommen die Community-Wertungen im Ranking?

Die angezeigten Community-Wertungen stammen aus der öffentlich zugänglichen **Rocky-Beach-Hörspielbewertung**. Der Datenstand wird regelmäßig automatisiert geprüft und innerhalb des Projekts aktualisiert.

Dabei werden Folgennummer und Titel vor der Übernahme gegeneinander geprüft. Liefert die Quelle eine unerwartete Ansicht oder passen Zuordnungen nicht, wird der neue Stand nicht veröffentlicht und Die Fallkartei verwendet weiterhin den zuletzt gültigen Datenstand.

Die installierte App fragt Rocky Beach nicht bei jedem Öffnen direkt ab. Sie lädt den geprüften Datenstand über die eigene GitHub-Pages-Bereitstellung und kann bei fehlender Verbindung auf bereits vorhandene Werte zurückfallen.

### Welche Filter gibt es für Empfehlungen?

Empfehlungen können unter anderem nach folgenden Kriterien eingeschränkt werden:

- Stimmung
- Länge
- Ära
- Autor
- Hörstatus

Dadurch kannst du zum Beispiel gezielt nach einer noch ungehörten längeren Folge aus einer bestimmten Ära suchen.

### Kann ich mir auch bereits gehörte Folgen empfehlen lassen?

Ja.

Der Hörstatus kann so eingestellt werden, dass nur ungehörte, nur gehörte oder beide Arten von Folgen berücksichtigt werden.

Das ist besonders praktisch, wenn du nach einer Folge zum Wiederhören suchst.

---

## Smart Playlists

### Was ist eine Smart Playlist?

Bei einer Smart Playlist gibst du unter anderem eine gewünschte Hörzeit und weitere Kriterien vor.

Die Fallkartei stellt daraus automatisch einen Playlist-Vorschlag zusammen. Diesen kannst du prüfen, einzelne Folgendetails öffnen und anschließend speichern oder einen neuen Vorschlag erzeugen lassen.

### Was bedeutet „Zusammenhänge beachten“?

Wenn diese Option aktiviert ist, versucht die Fallkartei, **inhaltlich miteinander verbundene Folgen gemeinsam** in einen Smart-Playlist-Vorschlag einzubauen.

Das Verbindungsnetz berücksichtigt beispielsweise:

- direkte Fortsetzungen
- fortlaufende Handlungsstränge
- wiederkehrende Figuren
- wiederkehrende Gegenspieler
- Familien- oder Figurenbeziehungen
- wichtige Rückbezüge
- bestimmte wiederkehrende Schauplätze

Starke und eher optionale Verbindungen werden unterschiedlich gewichtet.

### Warum besteht eine Smart Playlist trotz „Zusammenhänge beachten“ nicht ausschließlich aus verbundenen Folgen?

Die gewünschte Hörzeit, deine Filter und die persönliche Empfehlung sollen weiterhin berücksichtigt werden.

Deshalb kann eine Gruppe zusammenhängender Folgen den **Kern** einer Smart Playlist bilden und anschließend durch weitere passende Folgen ergänzt werden.

### Werden alle Auftritte einer wiederkehrenden Figur gleich behandelt?

Nein.

Ein direkter Handlungsstrang ist für den Algorithmus wichtiger als ein kurzer oder lockerer Gastauftritt.

Dadurch soll zum Beispiel eine echte Fortsetzung stärker gewichtet werden als zwei Folgen, in denen lediglich dieselbe Nebenfigur vorkommt.

---

## Zusammenhänge & ähnliche Folgen

### Was ist der Unterschied zwischen „Zusammenhänge“ und „Ähnliche Folgen“?

**Zusammenhänge** bezeichnen konkrete Verbindungen zwischen Folgen, beispielsweise eine Fortsetzung, eine wiederkehrende Figur oder einen direkten Rückbezug.

**Ähnliche Folgen** müssen dagegen nicht zur selben Geschichte gehören. Sie werden eher aufgrund gemeinsamer Eigenschaften, Themen und des persönlichen Geschmacks vorgeschlagen.

### Wo sehe ich, welche Folgen zusammenhängen?

Wenn für eine Folge bekannte Verbindungen hinterlegt sind, erscheinen diese direkt in den **Folgendetails**.

Die verknüpften Folgen können dort direkt geöffnet werden.

### Woher stammen die hinterlegten Zusammenhänge?

Das Verbindungsnetz wird redaktionell gepflegt und aus öffentlich nachvollziehbaren Informationen sowie Community-Zusammenstellungen abgeleitet.

Die Verbindungen werden anschließend für Die Fallkartei kategorisiert und gewichtet.

Weitere Angaben zu Quellen und Rechten stehen in [ATTRIBUTIONS.md](./ATTRIBUTIONS.md).

---

## Folgen & Katalog

### Welche Folgen sind enthalten?

Der Katalog enthält die regulären Hörspielfolgen sowie ausgewählte zusätzliche Inhalte und eigenständige Specials.

Bestimmte angekündigte oder zukünftige Folgen können bereits als Vorschau im Katalog erscheinen.

### Warum sind nicht alle Live-Hörspiele als eigene Folge enthalten?

Live-Versionen, die lediglich eine bereits vorhandene Geschichte neu aufführen, werden nicht zusätzlich als eigene Folge angelegt.

Eigenständige Live-Geschichten können dagegen als Zusatzinhalt im Katalog enthalten sein.

### Warum zählt eine Folge nicht zu meinen 100 %?

Für den regulären 100-%-Fortschritt zählen nur dafür vorgesehene und bereits veröffentlichte Folgen.

Nicht oder noch nicht mitgerechnet werden beispielsweise:

- zukünftige, noch unveröffentlichte Folgen
- reine Platzhalter
- bestimmte Zusatzinhalte und eigenständige Specials außerhalb des normalen Katalogfortschritts

Dadurch kann eine bereits angekündigte Folge im Katalog sichtbar sein, ohne deinen aktuellen Fortschritt zu verändern.

### Warum wird eine zukünftige Folge schon angezeigt?

Angekündigte Folgen können bereits frühzeitig im Katalog erscheinen.

Solange sie noch nicht veröffentlicht wurden, zählen sie nicht zum normalen 100-%-Fortschritt.

### Warum fehlt bei einer Folge das Cover?

Cover und Teile der Metadaten werden teilweise über externe Quellen geladen.

Wenn ein Cover momentan nicht erreichbar ist, noch keine passende Quelle hinterlegt wurde oder du offline bist, zeigt Die Fallkartei stattdessen einen neutralen Platzhalter.

### Warum speichert das Repository die Cover nicht einfach selbst?

Die Cover sind geschützte Inhalte der jeweiligen Rechteinhaber.

Die Fallkartei speichert die externen Coverdateien deshalb nicht als eigenen Bestandteil des Katalogs im Repository.

---

## Bewertungen & Hörverlauf

### Wird eine Folge automatisch als gehört markiert, wenn ich sie bewerte?

Ja.

Eine Bewertung setzt voraus, dass die Folge gehört wurde. Deshalb wird sie beim Bewerten automatisch als gehört markiert.

### Kann ich eine Folge mehrfach gehört haben?

Ja.

Für eine Folge können mehrere Hörvorgänge gespeichert werden. Dadurch kann Die Fallkartei auch Wiederholungen beziehungsweise Wiederhör-Statistiken berücksichtigen.

### Was bedeutet „Wiedergehört“?

Eine Folge gilt als wiedergehört, wenn mehr als ein Hörvorgang für sie gespeichert wurde.

### Was passiert, wenn ich einen Hörvorgang lösche?

Wird ein einzelner von mehreren Hörvorgängen entfernt, bleiben die übrigen erhalten.

Wird der einzige vorhandene Hörvorgang einer Folge gelöscht, kann die Folge wieder als ungehört behandelt werden. Playlist-Zuordnungen oder persönliche Notizen bleiben davon grundsätzlich getrennt.

---

## Playlists & persönliche Organisation

### Kann ich eigene Playlists erstellen?

Ja.

Eigene Playlists können benannt und anschließend direkt mit Folgen gefüllt werden.

Unter **Listen** erscheinen deine eigenen Playlists sowie die aufklappbaren Bereiche **Essentials** und **Themen**. Eigene Playlists werden zunächst über das Formular angelegt; erst beim Speichern entsteht eine Liste.

### Wie kann ich eine Playlist umbenennen oder löschen?

Öffne eine eigene Playlist und tippe auf den **Stift** neben dem Namen oder der Beschreibung, um den Text direkt zu ändern. Bestätige mit **Speichern** oder verwirf die Änderung mit **Abbrechen**. Über den **Papierkorb** in der Listenübersicht kannst du eine eigene Playlist nach Bestätigung entfernen. Eine kurze **Rückgängig**-Möglichkeit steht anschließend zur Verfügung.

### Gibt es die kuratierten Playlists und „Passt dazu“ weiterhin?

Ja. **Essentials** und **Themen** bleiben erhalten und können bei Bedarf aufgeklappt werden. In eigenen Playlists stehen unter **Passt dazu** weiterhin passende Folgeempfehlungen bereit. Beim Hinzufügen per Suche werden bis zu zwölf Treffer angezeigt.

### Was ist „Als Nächstes“?

„Als Nächstes“ ist eine einfache Warteschlange für Folgen, die du bald hören möchtest.

Wird eine Folge daraus gehört beziehungsweise entsprechend aktualisiert, kann sie automatisch aus der Warteschlange entfernt werden.

### Kann ich meine Lieblingsfolgen selbst festlegen?

Ja.

Im Profil können persönliche Favoriten ausgewählt werden. Diese können auch im teilbaren Hörprofil erscheinen.

---

## Streaming

### Spielt Die Fallkartei die Hörspiele selbst ab?

Nein.

Die Fallkartei ist kein eigener Streamingdienst und stellt keine Audiodateien bereit.

Wenn passende Links vorhanden sind, kann eine Folge direkt bei einem externen Anbieter geöffnet werden.

### Welche Streamingdienste werden unterstützt?

Je nach vorhandenen Links können unter anderem folgende Anbieter erscheinen:

- Spotify
- Apple Music
- BookBeat
- Amazon Music
- YouTube Music
- Deezer
- Amazon

Du kannst einen bevorzugten Anbieter festlegen.

---

## Technik & Projekt

### Warum ist Die Fallkartei eine PWA und keine normale Store-App?

Als PWA kann dieselbe App auf mehreren Plattformen verwendet werden, ohne jeweils eine eigene App-Store-Version pflegen zu müssen.

Außerdem kann sie direkt aktualisiert werden und benötigt für ihre persönlichen Tracking-Funktionen weder Benutzerkonto noch eigenes Backend.

### Ist der Quellcode öffentlich?

Ja.

Das Repository ist öffentlich einsehbar:

https://github.com/LetsMAgic/fallkartei

Für das Repository wird derzeit keine Open-Source-Lizenz erteilt. Die öffentliche Bereitstellung bedeutet daher nicht automatisch, dass der Quellcode frei weiterverwendet werden darf.

### Kann ich Fehler oder Ideen melden?

Ja.

Hinweise, Fehlerberichte und Ideen sind willkommen. Sofern GitHub Issues im Repository aktiviert sind, können sie dort gemeldet werden.

Bei einem Fehler helfen möglichst genaue Angaben zum Gerät, Browser, zur installierten Version und zu den Schritten, mit denen sich das Problem reproduzieren lässt.

### Kann ich zum Projekt beitragen?

Grundsätzlich können Hinweise und Verbesserungsvorschläge eingebracht werden.

Bei Änderungen an Katalogdaten oder Folgen-Zusammenhängen sind nachvollziehbare Quellen besonders hilfreich.

---

## Weitere Informationen

- [App öffnen](https://letsmagic.github.io/fallkartei/)
- [README](./README.md)
- [Impressum](./IMPRESSUM.md)
- [Datenschutz](./PRIVACY.md)
- [Quellen & Rechte](./ATTRIBUTIONS.md)
- [Änderungen](./CHANGELOG.md)

---

*Die Fallkartei ist ein inoffizielles, nicht-kommerzielles Fanprojekt.*
