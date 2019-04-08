# Kurs zu fMRT-Datenanalyse mit Python (Sommersemester 2019)

In diesem Repository liegen die notebooks für unser Seminar zur Analyse von fMRT-Daten mit Python (https://ekvv.uni-bielefeld.de/kvv_publ/publ/vd?id=150894283)

### Inhaltsverzeichnis

* [Anschauen einer 3D-Datei mit nilearn](./notebooks/01-anatomisches-bild-anschauen.ipynb)
* [Eigenes Viewer-Tool erstellen](./notebooks/02-interaktive_visualisierung.ipynb)

### Notebooks ausführen

Die Datenanalyse erfolgt mit Python 3 unter Verwendung von mainly numpy, scipy, pandas, scikit-learn, nilearn, nistats, matplotlib, seaborn und jupyter.

Um die Skripte auszuführen, kann eine virtuelle Umgebung erstellt werden. Installieren Sie hierzu zunächst miniconda  
  
https://conda.io/miniconda.html  

Klonen Sie dann dieses GitHub-Repository und erstellen Sie eine neue Umgebung mit der requirements Datei

```shell
conda create --name fmri --file requirements.txt
```


Starten Sie dann die Umgebung

```shell
conda activate fmri
jupyter notebook
```

### Kontakt

Fragen und Anmerkungen bitte an [martin.wegrzyn@uni-bielefeld.de](mailto:martin.wegrzyn@uni-bielefeld.de)


