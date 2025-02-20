# Unsupervised Classification of Sea-Ice & Lead using Sentinel-2 & Sentinel 3
# Introduction

This project focuses on using unsupervised machine learning models (K-Means & GMM specifically) to classify sea ice and leads from both Sentinel-2 imagery and Sentinel-3 altimeter data.

In satellite imagery, leads can be identified through visual inspection or automated analysis that highlights differences in pixel values. Sentinel-3 radar altimetry measures surface height variations by sending radar pulses and analysing the reflected signals, differentiating between sea-ice and lead based on their different radar backscatter and elevation.

The first Jupyter notebook titled 'Sentinel_Collocation' shows the process of collocating Sentinel-3 altimeter data with Sentinel-2 optical data, and the second Jupyter notebook titled 'Unsupervised_Ice_Classification' applies K-Means and Gaussian Mixture Models to both datasets in order to perform classification of sea ice and leads. Detecting leads in the arctic regions is vital for understanding the polar climate system and for supporting marine navigation, ecosystem stabilisation efforts and local communities.

# Getting Started
# Required Packages
This notebook is run on GoogleColab and the following packages need to be installed before being able to run the notebook.

```python
pip install rasterio
```
```python
pip install netCDF4
```

The Sentinel-2 satellite images and Sentinel-3 altimetry data is sourced from the Copernicus browser, which is a free online tool to access Sentinel satellite imagery via https://browser.dataspace.copernicus.eu/.
A account is needed before you can download any images.


# Contact Details
If you have any further questions feel free to contact me on dominic.weisser.24@ucl.ac.uk

# Acknowledgements
This project forms part of the module 'AI4EO' run by Dr Michel Tsamados. Large portions of the code have been adapted from his previous work.
