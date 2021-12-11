# survey-multigraph-integration-methods

<p align="center">
  <img src="./Fig1.PNG">
</p>
<p align="center">
  <img src="./Fig2.PNG">
</p>

>A connectional brain template (CBT) is an integral graph-based fingrprint of a population of brain networks also regarded as an average connectome. CBTs are powerful tools for creating representative maps of brain connectivity, disentangling the typical from the atypical variations across the population samples. Estimating a well-centered and discriminative CBT for populations of heterogenous brain networks such as structural, functional, and morphological networks is more challenging since these networks sit on complex manifolds and there is no easy way to fuse them. Thus, we list here all papers of 7 years (2014-2020), some journals, and MICCAI (2019-2020) papers that fuse multiple brain network and identify biomarkers (distinctive connectivities fingerprinting) of different population such as healthy and disordered populations. The existing fusion models embedded in the papers are basing on:
* [geometric deep learning multi-view graph network normalization](#MultiGraph)
* [deep learning cluster-based graph network integration](#MultiGraph)
* [manifold optimization clustering-based network integratio](#MultiGraph)
* [machine learning cluster-based network fusion](#singleView)
 
If you like to update the file by adding the unlisted open-source articles, feel free to open an issue or submit a pull requests. You can also directly contact Nada Chaari at chaari17@itu.edu.tr. All contributions are very welcome! 

<a name="MultiGraph" />

## Graph integration and fusion 

### Single graph fusion
| Title                                                        | Paper | Author | Dataset | Code | Youtube Video |  Proceeding/Journal/Year |
|:------------------------------------------------------------:|:----------------------:|:----------------------:|:----------------------:|:----------------------:| :----------------------:|:----------------------: 
| Deep Graph Normalizer: A Geometric Deep Learning Approach for Estimating Connectional Brain Templates | [ARXIV](https://arxiv.org/pdf/2012.14131.pdf)  | Mustafa Burak Gurbuz |  [ADNI 3](http://adni.loni.usc.edu/)  | [Python](https://github.com/basiralab/DGN) | [10 min](https://www.youtube.com/watch?v=Q_WLY2ZNxRk) | MICCAI 2020 | 
| Clustering-Based Deep Brain MultiGraph Integrator Network for Learning Connectional Brain Templates| [LNCS](https://link.springer.com/chapter/10.1007/978-3-030-60365-6_11) | Ugur Demir| [ABIDE](http://fcon_1000.projects.nitrc.org/indi/abide/)   | [Python](https://github.com/basiralab/cMGINet) | __ | GRAIL MICCAI 2020|
| Estimation of Gender-Specific Connectional Brain Templates using Joint Multi-View Cortical Morphological Network Integration | [LNCS](https://link.springer.com/article/10.1007/s11682-020-00404-5)  | Nada Chaari | [GSP](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/25833)   | __ | __ | Brain Imaging and Behavior 2020|
| Estimation of Connectional Brain Templates using Selective Multi-View Network Normalization | [ScienceDirect](https://www.sciencedirect.com/science/article/pii/S1361841519301070)  | Salma Dhifallah |  [ABIDE](http://fcon_1000.projects.nitrc.org/indi/abide/)   | [Python](https://github.com/basiralab/netNorm-PY) | __ | Medical Image Analysis 2020|
| Clustering-based multi-view network fusion for estimating brain network atlases of healthy and disordered populations | [ScienceDirect](https://reader.elsevier.com/reader/sd/pii/S0165027018302954?token=C0FB1190D50158892D415B658E92752EBA2C2BCC282D226E9B3BC55F160D853C4FD8D15E0F796D1E64E3D4F51C54A76F&originRegion=eu-west-1&originCreation=20210630085236)  |  Salma Dhifallah |  [ADNI 3](http://adni.loni.usc.edu/)  | __ | __ |  Neuroscience Methods 2019

<a name="singleView" />

### Multi-graph integration

| Title                                                        | Paper | Author | Dataset | Code | Youtube Video | Proceeding/Journal/Year |
|:------------------------------------------------------------:|:----------------------:|:----------------------:|:----------------------:|:----------------------:| :----------------------:|:----------------------:  
| Supervised Multi-topology Network Cross-diffusion for Population-Driven Brain Network Atlas Estimation | [LNCS](https://link.springer.com/chapter/10.1007/978-3-030-59728-3_16)  | Islem Mhiri | [ADNI](https://link.springer.com/chapter/10.1007/978-3-030-59728-3_17) [ABIDE](http://fcon_1000.projects.nitrc.org/indi/abide/) | [Python]( https://github.com/basiralab/SM-netFusion-PY) | [5min](https://www.youtube.com/watch?v=-dDn8CT4mH0) | MICCAI 2020  
| Joint Functional Brain Network Atlas Estimation and Feature Selection for Neurological Disorder Diagnosis With Application to Autism | [ScienceDirect](https://www.sciencedirect.com/science/article/pii/S1361841519301367)  | Islem Mhiri | [ABIDE](http://fcon_1000.projects.nitrc.org/indi/abide/)   | [Python]( https://github.com/basiralab/NAGFS-PY) | __ | Medical Image Analysis 2019
| Similarity network fusion for aggregating data types on a genomic scale | [LNCS](https://www.nature.com/articles/nmeth.2810.pdf)  | Bo Wang  | [TCGA](https://www.cancer.gov/about-nci/organization/ccg/research/structural-genomics/tcga/using-tcga/technology)  | [Python](https://github.com/rmarkello/snfpy) | __ | Nature Methods 2014
