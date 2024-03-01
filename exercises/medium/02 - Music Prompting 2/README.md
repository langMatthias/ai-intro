# Music Prompting 2

In dieser Übung nutzen wir Colab Notebooks um Musik zu generieren. Um dich damit vertraut zu machen, könntest du zum Beispiel die [Einführung in Python Programmierung](exercises/medium/01 - Einführung in Python) bearbeiten.

## Generierung von symbolischen Daten (MIDI)

In dieser Übung nutzen wir ein Transformer-Modell, welches aus einem Text-Prompt MIDI-Noten generiert. Dafür folgen wir den Anweisungen im folgenden Colab Notebook:

[![Open In Colab][colab-badge]][colab-notebook1]

[colab-notebook1]: <https://colab.research.google.com/github/asigalov61/Los-Angeles-Music-Composer/blob/main/Los_Angeles_Music_Composer_TTM_Edition.ipynb>
[colab-badge]: <https://colab.research.google.com/assets/colab-badge.svg>

Zur Generierung dient ein Song-Titel und der Name eines Künstlers. Hier können allerdings auch andere Text-Prompts verwendet werden. Wie reagiert das Modell darauf? 

Folgende Parameter können angepasst werden:
- mit `number_of_tokens_to_generate` kann die Länge des generierten Musikstücks gesteuert werden. 
- `number_of_batches_to_generate` steuert die Anzahl der generierten Musikstücke.
- `temperature` steuert die Kreativität des Modells. Ein höherer Wert führt zu mehr Variationen, ein niedrigerer Wert zu konservativer Generierung bzw. mehr Wiederholungen.

Die generierten MIDI-Dateien können heruntergeladen und in einem MIDI-Player abgespielt werden. Dazu einfach in der linken Spalte auf das Ordner-Symbol klicken und die Dateien herunterladen.

## Generierung von Audio-Daten

In dieser Übung nutzen wir das MusicGen Transformer-Modell von Meta, welches aus einem Text-Prompt Audio generiert. Dafür folgen wir den Anweisungen im Colab Notebook:

[colab-notebook2]: <https://colab.research.google.com/drive/1ECmNEoXk8kvnLEMBMF2LY82E7XmIG4yu?usp=sharing>
[![Open In Colab][colab-badge]][colab-notebook2]

Das Colab Notebook startet eine Gradio-Oberfläche, in der ein Text-Prompt eingegeben werden kann. Das Modell generiert dann eine Audiodatei, die heruntergeladen und abgespielt werden kann. Es kann sein, dass die Gradio-Oberfläche einen Fehler bei der Generierung ausgibt. In diesem Fall kann es helfen, die Webseite erneut zu laden. Solange das Colab Notebook aktiv ist, ist auch die Gradio-Oberfläche erreichbar. 

Um genauer zu verstehen, wie das Modell funktioniert, kannst du dir auch folgende Website ansehen (https://ai.honu.io/papers/musicgen/) bzw. das Paper [Simple and Controllable Music Generation](https://arxiv.org/pdf/2306.05284.pdf) durchlesen.



