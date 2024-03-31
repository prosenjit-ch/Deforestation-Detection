# Deforestation-Detection
Satellite image segmentation using deep learning for deforestation detection


**Problem Statement**

Deforestation poses a significant threat to ecosystems, biodiversity, and sustainable development, particularly in regions like Rangamati. Despite conservation efforts, monitoring vast forested areas remains a daunting task. Traditional methods of monitoring rely heavily on manual observation, making them inefficient and often inaccurate. To address this challenge, the project aims to develop a Deforestation Detection System for Rangamati. 


**Dataset**

We developed a dataset for this project called ChtD Dataset which contains 820 images of different upazilas of the Rangamati District. In future, we will increase the amount of images including the images of Khagrachari and Bandarban District. 

For dataset preparation, some steps are followed which are given below:

1. First of all, We collected satellite images of the Rangamati District. 

2. Then, using the Labelme annotation tools the images were annotated. Then, the corresponding coordinates of the deforested regions were saved in the JSON files.

![Screenshot (31)](https://github.com/prosenjit-ch/Deforestation-Detection/assets/116121494/e9e5a267-272c-4fc2-a214-6aa6740d8fd6)

3. After that, using those coordinates of the deforested area, the masks were generated where the black area represents the non-deforested area and the white area represents the deforested area. 

![Screenshot (32)](https://github.com/prosenjit-ch/Deforestation-Detection/assets/116121494/36688221-2aa5-47c7-b752-eafdab7643b2)


**Implementation**

After evaluating different variants of the U-Net, we found that our Modified U-Net model performed well in segmenting the deforested area from the image. the overall operations performed by the system are represented in the given figure:

![Screenshot (33)](https://github.com/prosenjit-ch/Deforestation-Detection/assets/116121494/15690951-82d5-44ab-a8d3-9c7a1652ce71)







