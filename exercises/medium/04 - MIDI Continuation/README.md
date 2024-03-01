# MIDI Continuation

Schwierigsgrad: mittel

## MIDI Composer

Der MIDI Composer ist ein Transformer-Modell, welches auf dem [Los Angeles Datensatz](https://huggingface.co/datasets/projectlosangeles/Los-Angeles-MIDI-Dataset) trainiert wurde. Dieser Datensatz enthält ~405.000 MIDI-Dateien, die von verschiedenen Künstlern und Genres stammen. Das Modell ist als Huggingface Space verfügbar und kann direkt im Browser verwendet werden. 

https://huggingface.co/spaces/skytnt/midi-composer

Mach dich zunächst mit dem Modell vertraut indem du ein Beispiel auswählst und mit `generate` eine MIDI-Datei generierst. Das Modell nimmt als Input eine MIDI-Datei und generiert dafür eine Fortsetzung.
Nun kannst du auch mit eigenen MIDIs experimentieren.

Zudem können unterschiedliche Modelle, die auf anderen Daten trainiert wurden, ausgewählt werden. 

Experimentiere auch mit unterschiedlichen Parametern:

- 'use first n midi events as prompt` gibt an, wie viele MIDI-Events als Prompt verwendet werden.
- `generate n midi events` gibt an, wie viele MIDI-Events generiert werden.
- unter `options: temperature` kann die Temperatur des Modells eingestellt werden. Eine höhere Temperatur führt zu mehr Zufälligkeit in der Generierung.

Das Modell ist auch als Colab Notebook verfügbar. Mache dich mit dem Code vertraut und versuche nun mit dem Python Code eine MIDI-Datei zu generieren.

[![Open In Colab][colab-badge]][colab-notebook1]

[colab-notebook1]: <https://colab.research.google.com/github/langMatthias/ai-intro/blob/main/exercises/medium/01 - MIDI Continuation/Los_Angeles_Music_Composer_Edition.ipynb>
[colab-badge]: <https://colab.research.google.com/assets/colab-badge.svg>



## Magenta Studio
Magenta Studio ist eine Plugin-Suite für Ableton Live. Folgende Funktionen werden unterstützt:
- Continue: Generiere eine Fortsetzung einer MIDI (vgl. MIDI Composer)
- Generate: Generiere eine MIDI-Datei ohne Prompt
- Interpolate: Interpoliere zwischen zwei Drum Beats oder Melodien
- Groove: Verändere Timing und Anschlagsstärke von Drum Grooves um ein menschlischeres Feeling zu erzeugen
- Drumify: Generiere ein Drum Beat zu einem anderen Input (z.B. Melodie, Bassline)

https://magenta.tensorflow.org/studio/

Es gibt auch Standalone Versionen, bei denen allerdings nicht garantiert ist, dass sie noch funktionieren:
https://magenta.tensorflow.org/v1/studio/standalone


## Open MuseNet

Open MuseNet ist eine Open-Source Nachimplementierung von OpenAI's MuseNet. Das Modell ist als Colab Notebook verfügbar und kann direkt im Browser verwendet werden. Im Bereich `Model Name` können sogar unterschiedliche Modelle ausgewählt werden. Ähnlich zu den vorherigen Modellen kann eine MIDI-Datei als Prompt hochgeladen werden oder ohne Prompt eine MIDI-Datei generiert werden. Die generierte Datei liegt dann als aiOut.mid im Colab-Workspace.

[![Open In Colab][colab-badge]][colab-notebook2]

[colab-notebook2]: <https://colab.research.google.com/github/langMatthias/ai-intro/blob/main/exercises/medium/01 - MIDI Continuation/midgeneasy_prod3_0.ipynb>
[colab-badge]: <https://colab.research.google.com/assets/colab-badge.svg>


## Audio Continuation

Das Konzept der MIDI-Continuation kann auch auf Audio angewendet werden. Hierbei wird ein Audio-Modell mit einem Audio-File gefüttert und generiert daraufhin eine Fortsetzung. Zum Beispiel kann das MusicGen-Modell dafür genutzt werden: https://huggingface.co/spaces/radames/MusicGen-Continuation