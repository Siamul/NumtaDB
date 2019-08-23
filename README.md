# NumtaDB

This is a Bengali digits dataset collected and curated by Samiul Alam, Tahsin Reasat, Rashed Mohammad Doha and Ahmed Imtiaz Humayun.

Link to arxiv: https://arxiv.org/abs/1806.02452
Link to Kaggle Dataset: https://www.kaggle.com/BengaliAI/numta

The description given below is copied from the kaggle page link given above.

The dataset is a combination of six datasets that were gathered from different sources and at different times. However, each of them was checked rigorously under the same evaluation criterion so that all digits were at least legible to one human being without any prior knowledge. Descriptions of these datasets including collection methodology, image segmentation and extraction and image formats of these datasets are described in https://bengali.ai/datasets.

The sources are labeled from 'a' to 'f'. The training and testing sets have separate subsets depending on the source of the data (training-a, testing-a, etc.). All the datasets have been partitioned into training and testing sets so that handwriting from the same subject/contributor is not present in both. Dataset-f had no corresponding metadata for contributors for which all of it was added to the testing set (testing-f). The metric for the competition is selected to be the Unweighted Average Accuracy (UAA). Starter codes for the competition are available at https://github.com/BengaliAI.

Two augmented datasets (augmented from test images of dataset 'a' and 'c') are appended to the testing set which consists of the following augmentations:
    Spatial Transformations: Rotation, Translation, Shear, Height/Width Shift, Channel Shift, Zoom.
    Brightness, Contrast, Saturation, Hue shifts, Noise.
    Occlusions.
    Superimposition (to simulate the effect of text being visible from the other side of a page).
