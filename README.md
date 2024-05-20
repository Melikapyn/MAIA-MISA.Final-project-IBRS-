# MAIA-MISA.Final-project-IBRS-


In this project, we focus on the segmentation of the three primary brain tissues - cerebrospinal fluid (CSF), gray matter (GM), and white matter (WM) - using the brain MRI data from the IBSR 18 dataset. Our approach integrates two key methodologies: traditional techniques involving multi-atlas and probabilistic atlas models, and advanced methods utilizing deep learning, specifically the U-net model. The objective was to identify the most effective segmentation strategy for our specific problem. Through attentive experimentation, we achieved Dice scores of 0.81, 0.89, and 0.80 for CSF, GM, and WM respectively using a single probabilistic atlas. Notably, the U-net model yielded even higher scores of 0.89, 0.94, and 0.93 for each tissue type in sequence.



## Dataset
Our project employed the IBSR 18 MRI dataset, which includes 18 T1-weighted MRI images from healthy individuals, all of whom have undergone skull-stripping. This dataset was divided as follows for our project purposes:

• Training set: 10 images, all with ground truth labels
• Validation set: 5 images, each with ground truth labels 
• Test set: 3 images, without ground truth labels

The dataset is characterized by its variability in spatial resolution and intensity distribution across the images. Each image has the same number of slices (256, 128, 256), yet they differ in pixel size across different dimensions. Specifically, the dataset encompasses three distinct pixel size categories. The following table details the pixel size distribution across the training and validation sets:
