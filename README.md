# ml-kmeans-clustering

[![Open in Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Jam-Reut/ml-kmeans-clustering/HEAD?labpath=kmeans-clustering.ipynb)


## 🚀 Projektbeschreibung

In diesem Projekt wird der **K Means Clustering Algorithmus** angewendet, um Universitäten in den USA automatisch in zwei Gruppen zu unterteilen: **Private** und **Öffentliche**. 
Obwohl die tatsächliche Zugehörigkeit im Datensatz vorhanden ist, wird sie nur zur nachträglichen Bewertung verwendet, da K Means ein **Unsupervised Learning** Verfahren ist.
Am Ende erfolgt eine Auswertung mit **Confusion Matrix** und **Classification Report**, jedoch rein theoretisch, da diese bei echten Anwendungsfällen i.d.R. nicht verfügbar wären.

## Projektstruktur

ml-kmeans-clustering:

- kmeans-clustering.ipynb # Hauptnotebook mit Projektlösung
- College_Data.csv # Datensatz mit Uni-Daten
- README.md # Projektdokumentation


### 🔧 Ausführen

1. Klicke auf den **Binder-Button oben**
2. Warte, bis JupyterLab gestartet ist (ca. 30 Sekunden)
3. Öffne das Notebook `kmeans-clustering.ipynb`
4. Führe die Zellen schrittweise aus

### 🎯 Ergebnis

- Der Algorithmus gruppiert Universitäten anhand ihrer Merkmale in zwei Cluster. 
- Eine Auswertung zeigt, wie gut diese Cluster mit den tatsächlichen Labels (private/public) übereinstimmen.

