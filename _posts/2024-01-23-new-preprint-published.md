---
layout: post
title: "New Preprint - Predicting the chemical space of RPLC"
---

## Exploring the Chemical Subspace of RPLC: a Data Driven Approach


The chemical space is comprised of a vast number of possible structures, of which an unknown portion comprises the human and environmental exposome. Such samples are frequently analyzed using non-targeted analysis via liquid chromatography (LC) coupled to high-resolution mass spectrometry often employing a reversed phase (RP) column. However, prior to analysis, the contents of these samples are unknown and could be comprised of thousands of known and unknown chemical constituents. Moreover, it is unknown which part of the chemical space is sufficiently retained and eluted using RPLC. Therefore, we present a generic framework that uses a data driven approach to predict whether molecules fall "inside", "maybe" inside, or "outside" of the RPLC subspace. Firstly, three retention index random forest (RF) regression models were constructed that showed that molecular fingerprints are able to predict RPLC retention behavior. Secondly, these models were used to setup the dataset for building a RPLC RF classification model. The RPLC classification model was able to correctly predict whether a chemical belonged to the RPLC subspace with an accuracy of 92% for the testing set. Finally, applying this model to the 91737 small molecules (i.e., <=1000 Da) in NORMAN SusDat showed that 19.1% fall "outside" of the RPLC subspace. Knowing which chemicals are outside of the RPLC subspace can assist in reducing potential candidates for library searching and avoid screening for chemicals that will not be present in RPLC data. [link](https://chemrxiv.org/engage/chemrxiv/article-details/65ae77639138d231617c37ef)


<img src="https://github.com/EMCMS/emcms/blob/gh-pages/assets/img/TOC_RPLC_ChemSpace.png?raw=true" alt="Graphical Abstract" width="1000"/> 

