# Unsupervised Classification of Sea-Ice & Lead using Sentinel-2 & Sentinel 3
![Sentinel 2 Sea-Ice & Lead Classification using a GMM](https://github.com/DomWeisser/Unsupervised_Sea-Ice-Lead_Classification/blob/main/GMM%20Clustering%20on%20Sentinel-2%20bands%20(4).png)
# Introduction

This project focuses on using unsupervised machine learning models (K-Means & GMM specifically) to classify sea ice and leads from both Sentinel-2 imagery and Sentinel-3 altimeter data. Detecting leads in the arctic regions is vital for understanding the polar climate and for supporting marine navigation, ecosystem stabilisation efforts and local communities.

In optical satellite imagery, leads can be identified through automated analysis that highlights differences in pixel values. On the other hand Sentinel-3 radar altimetry captures surface hieght variations by emitting radar pulses and analysing the reflected signals. It distinguishes sea-ice from leads by comparing their unique radar backscatter and elevation differences.

In this repository you can find 2 Jupyer notebooks.
1. 'Colocating Sentinel-3 OLCI/SRAL and Sentinal-2 Optical Data':

Shows the proccess of colocating Sentinel-3 data with Sentinel-2 optical data.

2. 'Unsupervised_Ice_Classification':

Applies K-means and Gaussian Mixture Models to both datasets in order to perform classification of sea-ice and leads.

# Getting Started
### Required Packages
This notebook is run on GoogleColab and the following packages need to be installed before being able to run the notebook.

```python
pip install rasterio
```
```python
pip install netCDF4
```
### Sentinel Data
The Sentinel-2 satellite images and Sentinel-3 altimetry data are sourced from the Copernicus browser, which is a free online tool to access Sentinel satellite imagery via https://browser.dataspace.copernicus.eu/.
A account is needed before you can download any images.


# Contact Details
If you have any further questions feel free to contact me on dominic.weisser.24@ucl.ac.uk

# Acknowledgements
This project forms part of the module 'AI4EO' at UCL run by Dr Michel Tsamados. Large portions of the code have been adapted from his previous work.
