## Next.Gen.Cluster.Heat.Map.Viewer
A GenePattern Module to view NGCHM in GenePattern Notebook.


## Use Next.Gen.Cluster.Heat.Map.Viewer with GenePattern Notebook 
1. After login, click on the dropdown list to insert a GenePattern Cell.
2. Select Next.Gen.Cluster.Heat.Map.Viewer module.
3. Upload a ngchm file or paste URL to a ngchm file. 
[Sample NGCHM File](https://github.com/MD-Anderson-Bioinformatics/GenePattern_NGCHM_Viewer/blob/master/test_data/Galaxy400x400-noCovariates.ngchm)

## Install Next.Gen.Cluster.Heat.Map.Viewer module on local GenePattern Server
1. Download [GenePattern](https://github.com/genepattern/genepattern-server/releases/tag/v3.9.11-rc.4%2Bb228), double click to install on local machine. 
2. Input Email, the app will ask to restart, double click on icon again.There is no need to install other modules if you only want to try NGCHM builder and viewer. 
3. Type "ant" to build zip file for the module.
4. Click on "Modules & Piplelines", then click on "Install from zip".
4. Chose to upload Next.Gen.Cluster.Heat.Map.Viewer.zip file in the build folder.

## Install GenePattern NoteBook manually to Jupyter Notebook 
1. Jupyter notebook is installed in Anaconda.
2. Install GenePattern notebook using pip.
```
pip install genepattern-notebook
```
3. Enable extenstion.
```
jupyter nbextension enable --py widgetsnbextension
jupyter nbextension install --py genepattern
jupyter nbextension enable --py genepattern
jupyter serverextension enable --py genepattern
jupyter nbextension install --py nbtools
jupyter nbextension enable --py nbtools
jupyter serverextension enable --py nbtools
```
4. Launch Jupyter.
```
jupyter notebook
```

[Guide](http://genepattern-notebook.org/install/) from GenePattern Notebook site.

## Use GenePattern Notebook docker
1. Install genepattern notebook from dockerhub.
```
docker pull genepattern/genepattern-notebook
```
2. Run genepattern notebook docker.
```
docker run -p 8889:8888 -name genepattern-notebook genepattern/genepattern-notebook
```
3. Copy the URL shown on the screen, paste into browser, change port number to 8889.


