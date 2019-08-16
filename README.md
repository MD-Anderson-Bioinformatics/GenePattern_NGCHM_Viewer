## GenePattern_NGCHM_Viewer
A GenePattern Module to view NGCHM in GenePattern Notebook.

## Install NGCHM_Viewer module on local GenePattern Server
1. Download [GenePattern](https://software.broadinstitute.org/cancer/software/genepattern/download/), double click to install on local machine. For Mac, Drag GenePattern into Application Folder. There is no need to install other modules if you only want to try NGCHM builder and viewer. 
2. Click on "Modules & Piplelines", then click on "Install from zip".
3. Upload the [NGCHM_Viewer.zip](https://github.com/MD-Anderson-Bioinformatics/GenePattern_NGCHM_Viewer/blob/master/NGCHM_Viewer.zip) file.

## Use NGCHM_Viewer with GenePattern Notebook
1. Install genepattern notebook from dockerhub.
```
docker pull genepattern/genepattern-notebook
```
2. Run genepattern notebook docker.
```
docker run -p 8889:8888 -name genepattern-notebook genepattern/genepattern-notebook
```
3. Copy the URL shown on the screen, paste into browser, change port number to 8889.
4. Click on the dropdown list to insert a GenePattern Cell.
5. Select NGCHM_Viewer module.
6. Upload a ngchm file or paste URL to a ngchm file. 
[Sample NGCHM File](https://github.com/MD-Anderson-Bioinformatics/GenePattern_NGCHM_Viewer/blob/master/test_data/Galaxy400x400-noCovariates.ngchm)
