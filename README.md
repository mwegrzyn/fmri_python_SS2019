# Course on fMRI Data Analysis with Python (Summer Term 2019)

This is the repository for our fmri analysis with python course (https://ekvv.uni-bielefeld.de/kvv_publ/publ/vd?id=150894283)

### Running this repository

Data analysis is performed with Python 3 using mainly numpy, scipy, pandas, scikit-learn, nilearn, nistats, matplotlib, seaborn and jupyter.

To run all the scipts, you can create a virtual environment, by first installing miniconda  
  
https://conda.io/miniconda.html  

Then you can create a virtual environment in the folder into which you cloned this repository

```shell
conda create --name fmri --file requirements.txt
```


Then you can start the environment like this


```shell
source activate fmri
jupyter notebook
```

or, under Windows, start 'anaconda prompt' and try

```shell
conda activate fmri
jupyter notebook
```

### Contact

For questions or comments please write to [martin.wegrzyn@uni-bielefeld.de](mailto:martin.wegrzyn@uni-bielefeld.de)


