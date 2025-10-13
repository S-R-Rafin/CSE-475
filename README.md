# Arsenicosis Skin Image Dataset

This repository contains a curated and annotated dataset of skin images collected to support research in dermatology and machine learning. The dataset focuses on classifying Arsenicosis-affected skin and healthy skin. It is intended for research in medical image analysis, disease detection, and computer vision applications.

## Dataset Description

The dataset consists of PNG images with a fixed dimension of 244 by 244 pixels. It includes a total of 10,374 images, comprising 8,892 augmented images and 1,482 original images. There are two classes in the dataset: Affected and Healthy. Each class contains 4,446 images.  

Images were collected from human subjects using four smartphones with different camera specifications. This dataset is suitable for dermatological studies and the development of machine learning models for automated classification.

## Data Access

The dataset is publicly available and can be accessed and downloaded from the following link:

[Download Dataset from Mendeley Data](https://data.mendeley.com/datasets/x4hgnjj5gv/2)

## Data Collection Locations

The data was collected from human subjects residing in four villages in Chapainawabganj District, Bangladesh. The specific locations are:

1. Village: Betbaria, Ward: 08, Union: Balidanga  
2. Village: Balubagan, Ward: 08, Union: Maharajpur  
3. Village: Dole Para, Ward: 09, Union: Maharajapur  
4. Village: Ramchandrapur Hat, Ward: 08, Union: Dohilpara, Sadar

## Folder Structure

The dataset is organized into two main directories: Original and Augmented. Both share the same structure. Within each directory, there are two subfolders named Affected and Healthy.  

- The Original directory contains 741 images in each class, totaling 1,482 original images.  
- The Augmented directory contains 4,446 images in each class, totaling 8,892 augmented images.

## Annotation File

An annotation file accompanies the dataset. It provides a unique Subject ID for each individual while preserving anonymity. The file contains three types of information: Subject ID, the village of origin, and the label (Affected or Healthy).  

A total of 741 original images were collected from 37 affected individuals and another 741 images from 76 healthy individuals. In addition, the dataset includes a list of non-arsenic-affected skin images that visually resemble arsenic lesions to help reduce false positives during model training.

## Potential Applications

The dataset can be used for multiple purposes, including:

- Dermatological research and early detection of arsenic-related skin conditions.  
- Machine learning and deep learning tasks for binary image classification.  
- Development of mobile health tools to assist rural healthcare workers.  
- Academic research projects and computer vision experiments.

## Ethical Considerations

All images were collected with informed consent. Personally identifiable information is not included, and Subject IDs are anonymized. The dataset must be used in accordance with ethical research guidelines and data protection regulations.

## Citation

If this dataset is used in research, please cite it as follows:

Arsenicosis Skin Image Dataset, Chapainawabganj, Bangladesh. Collected from rural subjects using mobile photography. (Year of Collection: 2023)

A formal citation will be added once the dataset is officially published.

## License

This dataset is distributed under the Creative Commons Attribution 4.0 International License (CC BY 4.0). Users are allowed to share and adapt the material with proper attribution.

## Acknowledgements

The contributors acknowledge the participation of the communities of Betbaria, Balubagan, Dole Para, and Ramchandrapur Hat. Special thanks are extended to the data collection team and dermatology experts involved in the annotation process.

