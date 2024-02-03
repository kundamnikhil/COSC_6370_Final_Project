# CT Lungs and Vessels Segmentation and Cancer Detection
Sure, here's the formatted text:

# Abstract

Accurate segmentation of medical images is crucial in contouring during radiation planning. Computed tomography (CT) scans are widely used for diagnosis, clinical research, and therapy planning. Segmentation divides an image into regions with equivalent qualities like brightness, contrast, and texture. In medical imaging, segmentation helps examine anatomical structures. Lung cancer is a significant health concern, with early detection crucial for effective treatment.

## Introduction

Computed tomography (CT) produces detailed images of various body regions, aiding in medical planning and disease detection. Lung segmentation, distinguishing lung boundaries from surrounding tissues, is vital for pulmonary image processing and clinical decision support systems. Our project aims to achieve the following objectives:

### Aim 1: CT Data Visualization and Intensity Analysis

- Visualize CT data with intensities and Hounsfield units.
- Experiment with different intensity levels and window values to enhance image efficiency.

### Aim 2: Lung Segmentation

- Calculate pixel dimensions to identify real areas and binarize images.
- Detect contours to isolate lung areas.

### Aim 3: Vessel Segmentation and Ratio Calculation

- Segment main vessels and compute vessel-to-lung area ratio for disease identification.

### Aim 4: Classification Model Training

- Train a model on masked images to predict lung tumor presence and type.

## Methods and Algorithms

CT imaging uses X-ray beams to generate 3D pixel intensities, with high-energy beams producing different densities in tissues. Hounsfield units quantify radiance and aid in diagnosis. We segment lungs based on intensity values, visualize contours, and isolate lung areas using polygon extraction. Scikit-learn and Pillow libraries facilitate image processing and analysis.

## Stepwise Implementation and Obtained Outputs

We slice Hounsfield ranges, binarize images, detect contours, and isolate lung areas. The resulting images highlight vessels and facilitate tumor classification. We train a classification model using masked images and achieve high accuracy. A user interface allows easy model access and input image classification.

## Conclusion and Future Scope

Segmentation based on Hounsfield units improves tumor detection and reduces model dependency. Our approach enhances interpretability and reduces computational load. Future improvements include automating image processing and training methods for custom datasets, leading to more accurate tumor detection in noisy CT images.

This structured approach improves lung cancer detection, enhances interpretability, and lays the foundation for further advancements in medical image analysis.

I have included a few test images for you to test the model in the notebook file.
![Screenshot_20221210_070251](https://github.com/kundamnikhil/COSC_6370_Final_Project/assets/43941418/e4d6b820-3be6-409f-83f7-7fe327ba9cd1)
![Screenshot_20221210_043136](https://github.com/kundamnikhil/COSC_6370_Final_Project/assets/43941418/7af85f4e-41ca-4a11-b0da-c8544410a24e)
![Screenshot_20221210_025307](https://github.com/kundamnikhil/COSC_6370_Final_Project/assets/43941418/afa7d5e7-8882-4fb2-9771-41e77025ef7b)
![Screenshot_20221210_025225](https://github.com/kundamnikhil/COSC_6370_Final_Project/assets/43941418/1151bb8a-8e25-43e4-92f8-635c8d8d101f)
![Screenshot_20221210_025046](https://github.com/kundamnikhil/COSC_6370_Final_Project/assets/43941418/3ab713f1-4c74-4e92-8a2c-4e07ee88b4f6)


For our trained model please download at : https://drive.google.com/file/d/1ykxzVFb4QI4-TIvK0e5hBY1I4y2mC7zJ/view?usp=share_link

For execution: Please run any of the python or python notebook files on collab. Steps are given in the notebook for execution.

For Dataset please download at: https://www.kaggle.com/datasets/mohamedhanyyy/chest-ctscan-images
