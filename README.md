# Elemente-der-Datenanalyse-und-der-Kuenstlichen-Intelligenz
Vorlesungsunterlagen für den Kurs "Elemente der Datenanalyse und der Künstlichen Intelligenz" 

Das Skript ist [unter diesem Link](https://pbrdng.github.io/Elemente-der-Datenanalyse-und-der-Kuenstlichen-Intelligenz/datenanalyse_und_KI.pdf) verfügbar.

## Julia und Jupyter Notebooks

Dieses Repository enthält [6 Jupyter Notebooks](https://github.com/PBrdng/Elemente-der-Datenanalyse-und-der-Kuenstlichen-Intelligenz/tree/main/Notebooks) (geschrieben in Julia 1.12):<br>

 * Julia Basics.
 * Matrizen und Bilder.
 * Modelle im maschinellen Lernen.
 * Klassifikation mit Hilfe neuronaler Netze.
 * Einfache Sprachmodelle.
 * Large Language Models.

Das Highlight in dieser Liste ist das letzte [Notebook über Large Language Models (LLMs)](https://github.com/PBrdng/Elemente-der-Datenanalyse-und-der-Kuenstlichen-Intelligenz/blob/main/Notebooks/06/Large-Language-Models.ipynb). 

Hier wird ein LLM von Grund auf implementiert und trainiert, so dass jeder Baustein eines LLMs nachvollzogen werden kann. 

Der Code in diesem Notebook basiert in weiten Teilen auf dem Blog Post [Generative transformer from first principles in Julia](https://liorsinai.github.io/machine-learning/2024/03/23/transformers-gpt.html) von [Lior Sinai](https://liorsinai.github.io) (danke an dieser Stelle für die Erlaubnis, den Code verwenden zu dürfen!). 

Als Datensatz nehmen wir die [Transkripte aus 393 Spongebob Episoden (auf englisch)](https://www.kaggle.com/datasets/mikhailgaerlan/spongebob-squarepants-completed-transcripts).

<br>
<br>

Um die Notebooks zu verwenden wie folgt vorgehen:

* Notebooks downloaden (per Klick auf den grünen
`Code` Button entweder als Zip File oder mit einem Git Client wie [Github Desktop](https://desktop.github.com)).
* Die neueste Version von Julia [downloaden](https://julialang.org/downloads/)
* Julia starten.
* In Julia per `]` in den Package manager wechseln.
* `add IJulia` ausführen
* Den Package manager per Backslash verlassen.
* `using IJulia` ausführen
* `notebook()` ausführen

Dann sollte sich ein Browserfenster öffnen, in dem lokal gespeicherte Notebooks geöffnet werden können.

