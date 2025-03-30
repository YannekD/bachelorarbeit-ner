# Bachelorarbeit – Named Entity Recognition in historischen Texten

Dieses Repository enthält den vollständigen Code, die Datenstruktur und die Experimente meiner Bachelorarbeit im Fach **Digital Humanities** an der Universität Göttingen.

## Titel der Arbeit

**Finetuning eines LLM zur Named Entity Recognition in historischen Texten – Eine Fallstudie mit Pamphlets der amerikanischen Revolution**

## Ziel

Ziel der Arbeit ist es, verschiedene Modellarchitekturen (BiLSTM-CRF, BERT, RoBERTa) auf einem manuell annotierten historischen Korpus zu vergleichen. Dabei werden insbesondere der Einfluss von Modelltyp, Modellgröße, domänenspezifischem Pretraining und Datenmenge untersucht.
🔍 Hinweise zur Reproduzierbarkeit

Dieses Repository enthält zahlreiche Jupyter Notebooks, die während der Bachelorarbeit verwendet wurden, um verschiedene Experimente durchzuführen. Viele dieser Notebooks entstanden iterativ und explorativ – sie enthalten daher:

    nicht immer sofort ausführbaren Code,

    teilweise harte Pfade zu lokalen Dateien.

📌 Wichtiger Hinweis:

Die Notebooks dienen nicht als direkt ausführbare Pipelines, sondern als Dokumentation des Entwicklungsprozesses. Wer bestimmte Experimente nachvollziehen möchte, sollte:

    Die entsprechenden Notebooks im Ordner experiments/ aufrufen,

    Sich die genutzten Pfade und Datenstrukturen ansehen,

    Gegebenenfalls Anpassungen an der eigenen Umgebung vornehmen.
