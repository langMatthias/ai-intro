# Music Prompting

Schwierigkeitsgrad: leicht

## MusicLM (von Google)
Ähnlich wie ChatGPT versuchen einzelne Anbieter auch Prompts zu nutzen um Musik zu generieren. Prompting bedeutet, dem Modell eine spezifische Anfrage oder Anleitung zu geben, um eine gewünschte Ausgabe zu erhalten. 

Das MusicLM Modell von Google ermöglicht es Musik mit einem Prompt als beschreibenden Text zu generieren. Dazu musst du dich auf der Website [https://aitestkitchen.withgoogle.com/tools/music-fx](https://aitestkitchen.withgoogle.com/tools/music-fx) einloggen. 
Auf der linken Seite kann ein Text eingeben werden, der als Prompt für die Musikgenerierung dient.
Das Modell generiert dann eine Audiodatei, die heruntergeladen und abgespielt werden kann. In den Settings können verschiedene Parameter eingestellt werden, wie z.B. die Länge des generierten Musikstücks oder ob ein Loop generiert werden soll.

Besonders interessant bei diesem Modell ist auch der DJ-Modus, indem unterschiedliche Prompts gewichtet werden können und das Modell live darauf reagiert.

Um besser zu verstehen, was das KI-Modell kann, kannst du dir auch Beispiel auf der [Website](https://google-research.github.io/seanet/musiclm/examples/) anhören oder sogar das Paper [MusicLM: Generating Music From Text](https://arxiv.org/pdf/2301.11325.pdf) lesen.

## Suno.ai
Suno.ai ermöglicht es, mit einem Prompt als beschreibenden Text, Musik, Liedtexte und sogar Albumcover zu generieren. Gehe dazu auf die Website https://www.suno.ai/ und höre dir ein paar Beispiele an. Um selbst zu generieren, klicke auf "Make a Song" und links unten auf "Sign Up". Dort kannst du dich mit einem Discord-, Google- oder Microsoft-Account einloggen. 

Nach dem Einloggen kannst du dann eine Song Description eingeben und Musik generieren lassen. In der frei verfügbaren Version erhält man 50 Credits, wobei ein generierter Song 5 Credits kostet.
Im `Custom Mode` können Lyrics, der Musik-Stil und auch der Titel definiert werden.

Experimentiere mit verschiedenen Prompts. Wie sehen gute Prompts aus? Wie kannst du das Modell dazu bringen, Musik in einem bestimmten Stil zu generieren? Wie kannst du das Modell dazu bringen, Musik zu einem bestimmten Thema zu generieren? 

## Andere Modelle
### MusicGen with Guidance
Das MusicGen-Modell kann zusätzlich zum Prompt auch eine Audio-Datei als Input nutzen. Das Modell generiert dann Musik, die zu der Audio-Datei passt. Das Modell kann auf der Huggingface Plattform getestet werden:
https://huggingface.co/spaces/Surn/UnlimitedMusicGen

Alternativer Link: https://huggingface.co/spaces/facebook/MusicGen

Das MusicGen-Modell kann auch zur Fortführung von Audio-Dateien genutzt werden. Dies kann in folgendem Huggingface Space ausprobiert werden:
https://huggingface.co/spaces/radames/MusicGen-Continuation

### AudioLDM
https://huggingface.co/spaces/haoheliu/audioldm2-text2audio-text2music
https://huggingface.co/spaces/haoheliu/AudioLDM_48K_Text-to-HiFiAudio_Generation

### MAGNeT
https://huggingface.co/spaces/fffiloni/MAGNet

### Riffusion
https://huggingface.co/spaces/fffiloni/spectrogram-to-music

## Prompt Upsampling

Das Konzept des Prompt Upsamplings nutzt Sprachmodelle wie ChatGPT um selbst Prompts zu verbessern. Hier wird das Sprachmodell genutzt um den Prompt auszuschmücken und damit bessere Ergebnisse zu erzielen. In folgendem Huggingface Space kann dieses Konzept ausprobiert werden: https://huggingface.co/spaces/reach-vb/musicgen-prompt-upsampling


## Weiterführende Übungen

Wenn du tiefer in Prompting einsteigen möchtest, kannst du auch den [zweiten Teil der Music Prompting Übungen](../medium/02 - Music Prompting 2/README.md) bearbeiten. Dort nutzen wir Colab Notebooks um Musik zu generieren.