# Interpolation

Schwierigkeitsgrad: leicht

Interpolation ist ein Konzept aus der linearen Algebra und bezieht sich auf die stufenweise Veränderung zwischen zwei Punkten in einem Raum. Mit dem Tool NSynth werden Klänge als Punkte oder Vektoren  in einem hochdimensionalen "latente Raum" dargestellt. Diese Darstellung erfolgt durch neuronale Netzwerke, die komplexe auditive Merkmale extrahieren und in einem abstrakten Raum kodieren.

## Klang-Interpolation

Die Interpolation zwischen den latenten Darstellungen zweier Klänge ermöglicht es uns, neue Klänge zu generieren, indem wir eine lineare Bewegung durch den latenten Raum zwischen den beiden Punkten durchführen. Dieser Prozess der linearen Interpolation erlaubt uns, subtile klangliche Übergänge zu erzeugen, indem wir Eigenschaften der Ausgangsklänge kombinieren.

Durch die Erforschung des latenten Raums können wir auch interessante Einblicke in die Struktur und Organisation von Klängen gewinnen. Ähnliche Klänge werden im latenten Raum nahe beieinander liegen, während unterschiedliche Klänge weiter voneinander entfernt sein werden. Dies ermöglicht es uns, Beziehungen zwischen verschiedenen Klängen zu erkennen und bietet eine Grundlage für die kreative Klangmanipulation und -exploration.

Experimentiere mit dem latenten Raum von NSynth:
https://experiments.withgoogle.com/ai/sound-maker/view/

Klicke auch auf das Fragezeichen in der rechten oberen Ecke, um besser zu verstehen, wie das Tool funktioniert. Du kannst auch ein MIDI-Keyboard anschließen und die Klänge direkt spielen.

## Interpolation zwischen musikalischen Stilen

Das MusicVAE-Modell von der Magenta Gruppe von Google ermöglicht es uns, zwischen verschiedenen musikalischen Stilen zu interpolieren. Dieses Modell lernt, musikalische Stile zu repräsentieren und kann uns dabei helfen, neue musikalische Ideen zu generieren, indem wir zwischen verschiedenen Stilen interpolieren. Auf der folgenden Website ist es möglich zwei MIDI-Dateien hochzuladen und eine Interpolation zwischen den beiden Stilen zu generieren:
https://codepen.io/iansimon/full/Bxgbgz/

Das Modell unterstützt sogar die Interpolation basierend auf einer vorher definierten Akkord-Folge:
https://codepen.io/iansimon/full/GGRYJZ