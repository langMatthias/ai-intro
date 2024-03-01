# Markov Chains

Schwierigkeitsgrad: mittel

In diesem Tutorial nutzen wir Markov-Ketten, um Musik zu generieren.

Mache dich zunächst mit dem Konzept der Markov-Ketten vertraut. Dazu kannst du folgenden Artikel lesen: https://setosa.io/ev/markov-chains/
Um das Verhalten von Markov-Ketten besser zu verstehen, kannst du auch die interaktive Demo unter https://setosa.io/markov/index.html ausprobieren. Verändere die Gewichte der Kanten und beobachte, wie sich das Verhalten des Modells ändert.

## Musik-Generierung mit Markov-Ketten

Markov-Ketten können auch zur Generierung von Musik verwendet werden. In der Musik-Generierung werden Markov-Ketten oft verwendet, um die Wahrscheinlichkeit zu modellieren, dass ein bestimmter Akkord oder eine bestimmte Note auf einen anderen Akkord oder eine andere Note folgt. Im folgenden Tutorial werden Markov-Ketten genutzt um jeweils die nächste Note vorherzusagen:


[![Open In Colab][colab-badge]][colab-notebook3]

[colab-notebook3]: <https://colab.research.google.com/drive/1DTfLU4euq13HOACdrpaaeXv3qmdZKIhh?usp=sharing>
[colab-badge]: <https://colab.research.google.com/assets/colab-badge.svg>




[![Open In Colab][colab-badge]][colab-notebook1]

[colab-notebook1]: <https://colab.research.google.com/github/langMatthias/ai-intro/blob/main/exercises/medium/01 - Einführung in Python/Mozarts_Würfelspiel.ipynb>
[colab-badge]: <https://colab.research.google.com/assets/colab-badge.svg>

Versuche wenn möglich die Aufgaben selbst zu lösen. Für den Fall, dass du nicht weiterkommst, findest du die Lösung ebenfalls auf Google Colab:

[![Open In Colab][colab-badge]][colab-notebook2]

[colab-notebook2]: <https://colab.research.google.com/github/langMatthias/ai-intro/blob/main/exercises/medium/01 - Einführung in Python/Mozarts_Würfelspiel_solution.ipynb>
[colab-badge]: <https://colab.research.google.com/assets/colab-badge.svg>
TODO: correct link


## Weiterführende Literatur

Das Kompositions-Framework [SCAMP](http://scamp.marcevanstein.com/index.html) bietet eine Markov-Ketten-Implementierung, die in der Lage ist, MIDI-Dateien zu verarbeiten. Die Dokumentation ist hier zu finden:

http://scamp.marcevanstein.com/scamp_extensions.process/scamp_extensions.process.markov.MarkovModel.html#scamp_extensions.process.markov.MarkovModel