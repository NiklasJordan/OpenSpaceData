# Bewerbung für Prototype Fund (Runde 9)

## OpenSpaceData.org (kurz: OSD)

### Ordne das Projekt einem Bereich zu.*
Data Literacy

### Beschreibe Dein Projekt kurz.

OpenSpaceData.org demokratisiert Satellitendaten. Ziel des Projekts ist es, eine Suche bereitzustellen, die das Finden von Daten für alle – unabhängig von technischen und fachlichen Kenntnissen – erleichtert. Dafür sollen frei verfügbare Satellitendaten, wie die der ESA oder NASA, zentralisiert auf OSD zusammenlaufen, um über eine Suchmaske den Zugang zu diesen zu erleichtern. Das Tool übersetzt die Anfrage des Nutzers in die passenden Parameter des Satellitenprogramms. Egal, ob Einzelpersonen (Journalisten, Wissenschaftler, Interessierte) oder Zusammenschlüsse (Initiativen, Vereine): Der Zugriff auf die Daten und die Nutzung dieser erhöht die demokratische Teilhabe an der Gesellschaft.

### Welches gesellschaftliche Problem willst Du mit Deinem Projekt lösen?*

Pro Tag liefern allein die 12 Copernicus-Satelliten der ESA eine Datenmenge von 250 TB. Das Problem: Oft braucht es technisches (APIs) und fachliches Wissen (Bestimmung der Sensoren, spezifische Parameter etc.), um Daten abzurufen. OSD soll einen einfachen Zugang zu diesen gesellschaftsrelevanten Informationen ermöglichen. Das gewährleistet, dass jeder – Bürger oder NGO – Ereignisse unabhängig einordnen kann. Ein Beispiel: Dank OSD kann man auf Nah-Echtzeit-Daten von Schadstoffemissionen zugreifen. So können NGOs oder Journalisten drohende Umweltkatastrophen schnell erkennen. Gleiches gilt für humanitäre Organisationen, die nach Katastrophen wie der Explosion in Beirut, handeln wollen.

### Wie willst Du Dein Projekt technisch umsetzen?*

Satelliten erfassen, wie Digitalkameras, Wellenlängen. Sie nehmen aber einen größeren Bereich des elektromagnetischen Spektrums auf. Bänder, die einen bestimmten Bereich von Wellenlängen abbilden, bilden ein Satellitenbild.

Was aber den Nutzer interessiert: Gesundheitszustand eines Waldes, Oberflächentemperatur von Berlin, Ausmaß der Überschwemmung in Florida.

Für unterschiedliche Aufträge ist die Messung unterschiedlicher Wellenlängen des elmag. Spektrums notwendig – bspw. reflektiert Wasser eine andere Wellenlänge als Asphalt. Der Nutzer muss das aber nicht wissen, denn das macht OSD (Wahl der Sensoren, Bänder, Wellenlängen etc.). Es übersetzt die Aufträge in die technischen Parameter, die notwendig sind, um die gewünschten Satellitendaten abzurufen. Der Nutzer erhält das passende Satellitenbild, das nicht auf dem Server liegt, sondern verlinkt ist. Es kann gedownloadet und mit jedem üblichen Image Viewer geöffnet werden (da es oft TIFF-Dateien sind).

Möchte man spezifische Werte wie den NDVI, der den Gesundheitszustand von Pflanzen von -1 bis +1 beschreibt, ermitteln, muss man verschiedene Bänder miteinander kombinieren. OSD stellt Anleitungen bereit, die angeben, wie und mit welchen Tools man die Bänder miteinander kombinieren kann, um den gewünschten Wert zu erhalten.

### Welche ähnlichen Lösungen gibt es schon, und was wird Dein Projekt anders bzw. besser machen?*

Es gibt kommerzielle Anbieter, die ein einfaches UI anbieten. Allerdings wird Fachkenntnis vorausgesetzt und eine monatliche Nutzungsgebühr erhoben. Andere filtern ausschließlich Formeln für Bandkombinationen oder bieten lediglich analysierte Daten und nicht die Rohdaten selbst an. Mein Tool soll freie Daten durchsuchbar machen und einen Einstieg in die Nutzung dieser geben.

### Wer ist die Zielgruppe und wie soll Dein Tool sie erreichen?*

Meine Zielgruppe sind primär NGOs und Initiativen aus den Bereichen Umwelt und humanitärer Hilfe sowie Katastrophen- und Entwicklungshilfen. Aber auch (Bürger-)Journalisten, Blogger, (Bürger-)Wissenschaftler und Interessierte sollen OSD für Recherchen und Analysen nutzen können. 

Auf Konferenzen, in Webinaren und Online-Tutorials plane ich, OSD bekannter zu machen. Dafür bin ich in verschiedenen Communities, wie CodeForAll, The Spatial Community, HOT OSM und der Society for Conservation GIS vernetzt. Außerdem möchte ich das Thema in verschiedenen Publikationen (bspw. reset.org, geoObserver Blog) streuen, indem ich aktiv Gastartikel und Interviews anbiete. 

### Hast Du schon an der Idee gearbeitet? Wenn ja, beschreibe kurz den aktuellen Stand und erkläre die Neuerung.*

OSD ist ein Projekt, an dem ich kürzlich begonnen habe zu arbeiten. In der GitHub Repo ist noch kein Code vorhanden, ich bearbeite aber transparent und für jeden sichtbar Idee und Konzept. Das wird bereits fortlaufend erweitert.

In diesem Jahr plane ich, einen MVP als Klickdummy zu erstellen, um diesen anschließend in Nutzer-Interviews zu validieren. Ziel ist es, konkrete Anforderungen der Endnutzer zu ermitteln.

Für den Prototyp werde ich mich vorerst auf das Satellitenprogramm der ESA (Copernicus Programm) fokussieren. Perspektivisch sind auch frei verfügbare Daten weiterer Weltraumagenturen relevant für das Projekt.

### Skizziere kurz die wichtigsten Meilensteine, die Du (bzw. das Team) im Förderzeitraum umsetzen willst.*

M1: Architektur (35%*)
Planung einer geeigneten Informationsarchitektur (mit nötigen Relationen, Abhängigkeite etc.); aufsetzen der Datenbankstruktur; Anbindung der Schnittstelle der ESA.

M2: Backend (35%*)
Die Suchlogik wird entwickelt, damit eine entsprechende Suchanfrage mit den technischen Parametern der Datenbank abgeglichen werden kann. Im Ergebnis werden die gewünschten Daten ausgegeben.

M3: Interface (30%*)
Zuletzt wird das User Interface umgesetzt. Es enthält Suchmaske, Ausgabe der Daten und Informationen/Anleitungen zur Weiterverwendung der Daten, sodass keine technischen Kenntnisse zur Nutzung von Satellitendaten notwendig sind.

*Anzahl der Arbeitsstunden für den Meilenstein
