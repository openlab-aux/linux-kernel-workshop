<!-- Context_explanation START -->

Der Linux Kernel ist das pulsierende Herzstück jedes Debian Servers,
jedes Ubuntu Desktop Systems und jedes Android Smartphones.
Der Quellcode ist gleichzeitig für jedermann offen einseh- und auch für den
eigenen Computer erweiter- und anpassbar. So können neue Funktionen oder
Treiber für neue Hardware hinzugefügt werden.

Oft möchte man jedoch, dass die eigenen Änderungen Teil des großen offiziellen Linux Kernel Projektes werden und damit auf alle der oben
genannten Geräte verteilt werden. Dazu muss man die eigenen Änderungen
als Patch an den richtigen Kernel Maintainer schicken. Der entscheidet
dann ob die Änderungen in den Kernel kommen. Namen oder Titel
sind bei dieser Entscheidung völlig bedeutungslos. Nicht aber Code Qualität, Sauberkeit und äußere Form.

<!-- Context_explanation END   -->

Mit diesem Workshop möchte ich kernel-interesierten Programmieren helfen die Schritte zum ersten *Linux Kernel Commit* zu gehen.

Dazu werde ich zum einen auf die technischen Aspekte des Kernel-codes eingehen.
Hauptsächlich werde ich jedoch das notwendige organisatorische 'Drumherum' erklären,
also wie das Einsenden der Patches läuft, worauf man achten muss usw.

### Es gibt Antworten zu

 * Wie und wo fange ich an?
 * Welches Repository ist für mich relevant?
 * Wie kompiliere und teste ich meinen Kernelpatch?
 * Was sind interesennte 'Baustellen' zum Anfangen?
 * Wie kommuniziere ich mit meinem Maintainer (Mailinglisten)
 * Wohin und wie sende ich meine(n) Code/Patches

### Inhalt und Zeitplan

 1. Einleitung (*10 min*)
 2. Die Repositories und der Entwicklungsprozess (*15 min*)
 3. Der Sourcecode (Überblick) (*10 min*)
 4. Kompilieren und Testen (*20 min*)
 5. Mailinglisten, Konventionen und Umgangsformen (*20 min*)
 6. Patches bauen und senden mit git-send-email (*20 min*)
 7. Buchempfehlungen und gute Quellen (kernelnewbies) (*5 min*)
 8. Fragen und Zeitpuffer (*20 min*)

### Notwendiges Vorwissen

 * Erfahrung im Umgang mit *git*
 * Erfahrung mit der Programmiersprache *C* insbesondere *Pointer*
 * Souveräner Umgang mit der *Shell*
 * 1-2 Jahre Erfahrung mit *Linux* oder einem anderen *Unix*
