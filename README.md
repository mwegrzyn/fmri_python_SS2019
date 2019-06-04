# Kurs zu fMRT-Datenanalyse mit Python (Sommersemester 2019)

In diesem Repository liegen die notebooks für unser Seminar zur Analyse von fMRT-Daten mit Python (https://ekvv.uni-bielefeld.de/kvv_publ/publ/vd?id=150894283)

### Inhaltsverzeichnis

* [Anschauen einer 3D-Datei mit nilearn](./notebooks/01-anatomisches-bild-anschauen.ipynb)
* [Eigenes Viewer-Tool erstellen](./notebooks/02-interaktive_visualisierung.ipynb)
* [Daten aus fMRT-Zeitserie extrahieren](./notebooks/03-fmrt-zeitverlaufe.ipynb)
* [Eine Aktivierungskarte erstellen](./notebooks/04-unser-erstes-hirnbild.ipynb)
* [Aktivierungskarten für verschiedene Bedingungen erstellen](./notebooks/05-verschiedene-bedingungen-plotten.ipynb)
* [Aktivierung einer Region als Design verwenden (Seed-To-Brain Korrelationen)](./notebooks/06-correlation-mit-seed.ipynb)
* [Ein Modell der erwarteten hämodynamischen Antwort erstellen](./notebooks/07-hrf-modell.ipynb)
* [Ein Hirnbild der Korrelationen mit dem HRF-Modell erstellen](./notebooks/08-whole-brain-analyse-mit-hrf.ipynb)
* ["Beta"-Hirnkarten erstellen](./notebooks/notebooks/09-beta-images.ipynb)
  * Bonus-Notebooks:
    * [Percent Signal Change](./notebooks/09-bonus-percent-signal-change.ipynb)
    * [Drift Modellieren](./notebooks/09-bonus-drift-models.ipynb)

### Notebooks ausführen

Die Datenanalyse erfolgt mit Python 3 unter Verwendung von numpy, scipy, pandas, scikit-learn, nilearn, nistats, matplotlib, seaborn und jupyter.

Um die Skripte auszuführen, kann eine virtuelle Umgebung erstellt werden. Installieren Sie hierzu zunächst miniconda  
  
https://conda.io/miniconda.html  

Klonen Sie dann dieses GitHub-Repository und erstellen Sie eine neue Umgebung mit der requirements Datei

```shell
conda create --name fmri --file requirements.txt -c conda-forge
```

oder, für die aktuelle Version der Module

```shell
conda create --name fmri 
conda install --name fmri -c conda-forge nilearn pandas jupyter matplotlib seaborn nibabel numpy scipy scikit-learn statsmodels nistats
```


Starten Sie dann die Umgebung

```shell
conda activate fmri
jupyter notebook
```

### Kontakt

Fragen und Anmerkungen bitte an [martin.wegrzyn@uni-bielefeld.de](mailto:martin.wegrzyn@uni-bielefeld.de)


