# Coral Reef Annotations

![coral_generic](docs/assets/coral_intro_unep.jpeg)
*unep.org/*

## Introduction
Coral reef ecosystems cover around 0.1% of the world's ocean yet boast a wealth of natural diversity. It has been estimated that around 25% of marine species inhabit this area. However, in recent years there has been a sharp decline in the health of coral reefs around the world. This is due to a myriad of reasons including climate change, pollution, and unsustainable coastal development (UNEP). Recent statistics show that 14% of the world’s corals were lost between 2009 and 2018 (Global Coral Reef Monitoring Network). This trend is projected to continue with about 70%-90% in live corals by 2050 (UNEP). 

In order to aid conservation efforts and inform environmental policies, it is important to keep track of the coverage statistics of coral reefs. Aerial and satellite images have been used for this purpose (CITE). To further understand the factors which contribute to the decline and abundance of coral reefs, marine ecologists usually need to perform in situ studies in order to determine the number of different coral species and algae in a given area. 

Recent efforts have been made to create high-quality survey images of coral reefs. However, manual annotation is often tedious and expensive and the expertise of marine ecologists can be better used elsewhere. It has been claimed that as little as 1-2 % of captured images get annotated. In this project, I explore ways to perform automatic annotation of high-resolution, close-range survey images of coral reefs. The dataset for this project is taken from the Moorea Coral Reef Long Term Ecological Research (MCRLTER). 

## Moorea Labeled Corals Dataset (MLC)

The Moorea Labeled Corals dataset contains 2055 high-resolution underwater images taken from six sites around the island of Moorea in French Polynesia. The data is evenly distributed across 3 years (2008, 2009, 2010).  The data is annotated using random sampling, in which experts assign one of 30 labels to randomly selected pixels in the image. Each image contains roughly 200 annotated points. Nine classes account for 96% of the dataset. These can be further divided into corals and non-corals.

![sample_patches](docs/assets/sample_patches.jpeg)
*Sample Patches from the MLC Dataset*


The main task to be automated is then to label random pixels in a given image. The authors of the dataset argue that “A full manual segmentation would be too time-consuming to collect and neither bounding boxes nor gross image labels provide the level of detail needed.” Additionally, there is high variability in the size, color, and shape of corals and the boundaries are often ambiguous. 

## Method

### Data & Preprocessing

### Classification Models

### Results

### Discussion

### Further Work 


