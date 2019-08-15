# GenePattern_NGCHM_Viewer
A GenePattern Module to view NGCHM in GenePattern Notebook.

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
