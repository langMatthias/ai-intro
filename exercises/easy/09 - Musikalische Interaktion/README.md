# Musical interaction

Schwierigkeitsgrad: leicht

Im Folgenden betrachen wir zwei Modelle, mit denen wir direkt interagieren und improvisieren können. 

Hinweis: Für diese Übung empfiehlt sich ein MIDI-Keyboard oder ein anderes MIDI-fähiges Instrument.

## AI Duet
Das AI Duet-Modell von Google ermöglicht es, direkt mit einem KI-Modell zu interagieren. Das Modell reagiert auf musikalische Eingaben und generiert daraufhin eine Antwort:

https://experiments.withgoogle.com/ai/ai-duet/view/


Schaue dir zunächst das Video dazu an, welches du hinter dem "How it works" Button findest. Verbinde dann ein MIDI-fähiges Gerät mit deinem Computer und experimentiere mit dem Modell. Wie reagiert das Modell auf deine musikalischen Eingaben? Hat das Modell ein Verständis für musikalische Strukturen oder Stilen?

## Performance RNN

Das Performance RNN-Modell von Magenta ist ein weiteres Modell, mit dem du direkt interagieren kannst. Dieses Modell ist auf ungefähr 1400 MIDI-Aufnahmen der Yamaha e-Piano Competition trainiert. Mit einem verbundenen MIDI-Gerät kann hier nicht direkt gespielt, sondern das Modell auf bestimmte Töne konditioniert werden. Vereinfacht gesagt, erhöht ein gehaltener Ton die Wahrscheinlichkeit, dass das Modell diesen Ton in der generierten Antwort verwendet. Ist ein Konzept von Harmonie und Melodie erkennbar? Wie geht das Modell mit Dissonanzen um?

https://magenta.tensorflow.org/demos/performance_rnn/