## 	Next.Gen.Clustered.Heat.Map.Viewer
A GenePattern Module to view Next-Generation Clustered Heat Maps (NG-CHMs) in GenePattern Notebook.
For details about NG-CHM, please check [NG-CHMs website](http://www.ngchm.net/)

## Description
Clustered heat maps are the most frequently used graphics for visualization of molecular profiling data in biology, appearing in many thousands of publications—but as static images.

To provide more capability for exploration of large data matrices, we developed highly interactive “Next-Generation” Clustered Heat Maps (NG-CHMs). NG-CHMs enable the user to zoom and navigate dynamically and link out to dozens of external data resources and tools. NG-CHMs exploit recent advances in web technology to improve performance, provide a highly-responsive user experience, and facilitate deep exploration of the biology (or other science) behind the image.

NG-CHMs include the following interactive capabilities (among many others):

* Extreme zooming without loss of resolution for drill-down into big data matrices.
* Fluent navigation.
* Link-outs from labels or pixels to a variety of pertinent annotation resources, including GeneCards, PubMed, the Gene Ontology, Google, and cBioPortal.
* Flexible real-time recoloring.
* High-resolution graphics that meet the requirements of all major journals.
* Annotation with pathway data.
* Capture of all metadata necessary to reproduce any chosen state of the map, even months or years later.

## Input
This module will take .ngchm file generated from GenePattern [Next.Gen.Clustered.Heat.Map.Builder](https://md-anderson-bioinformatics.github.io/GenePattern_NGCHM_BasicBuilder/) or any other NGCHM Builders ([Galaxy Builder](https://github.com/MD-Anderson-Bioinformatics/NG-CHM_Galaxy),[R buidler](https://github.com/MD-Anderson-Bioinformatics/NGCHM-R) or [online builder](http://build.ngchm.net/NGCHM-web-builder/)) and display the NGCHM in jupyter notebook.

## Use Next.Generation.Clustered.Heat.Map.Viewer with GenePattern Notebook 
1. Download [Sample NGCHM file](https://github.com/MD-Anderson-Bioinformatics/GenePattern_NGCHM_Viewer/blob/master/test_data/400x400.ngchm) to local.
2. After loading viewer module, upload 400x400.ngchm by clicking on ```Upload File``` button and choose the sample NGCHM file. If NGCHM file is generated using [Next.Gen.Clustered.Heat.Map.Builder](https://md-anderson-bioinformatics.github.io/GenePattern_NGCHM_BasicBuilder/), you could just paste the URL of generated NGCHM into field ```ngchm file```.
3. Click ```Run```.
4. Upon the completion of loading NGCHM file, you will see the loaded heatmap in notebook. 
5. For better visualization, click on the gear icon at the upper right corner of the viewer cell and choose ```Pop Out Visualizer```. The NGCHM viewer will open in another tab. 

## Output
You could view NG-CHM inside the notebook, and perform all the operations. If you prefer a full size NG-CHM, click on the gear icon at the upper right corner of the cell, select "Pop Out Visualizer", the NG-CHM will open in another tab. For more operations on NG-CHM, please check NG-CHMs website](http://www.ngchm.net/).


