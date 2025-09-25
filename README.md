# Coffee Gear Object Detection Dataset (Looker Studio & Python)

## Overview
This project is a small, self-annotated dataset of **coffee gear** for object detection tasks.
It was created as a portfolio piece to demonstrate skills in **data annotation, dataset QA,
and analysis**. All images were manually labeled in **Label Studio**.

## Classes
- 0: Cup
- 1: V60
- 2: Chemex
- 3: Kettle
- 4: CoffeeMachine

## Dataset
- Images: 250
- Objects (bounding boxes): 405
- Annotation tool: Label Studio
- Export formats: YOLO + COCO

## Annotation Process
- Pilot: 50 images → refined guidelines
- Final: 250 images
- QA: random check of 15 images (consistent, no major corrections)

![Label Studio Screenshot](https://github.com/IzaKam13/Portfolio-4_Data_Annotation_Looker-Studio_Python/blob/main/reports/figures/labelstudio_example.png)

## Analysis
### Python  code
![Python code](https://github.com/IzaKam13/Portfolio-4_Data_Annotation_Looker-Studio_Python/blob/main/notebooks/annotation-coffee-analysis.ipynb)

### Class distribution
![Class distribution](https://github.com/IzaKam13/Portfolio-4_Data_Annotation_Looker-Studio_Python/blob/main/reports/figures/class_distribution.png)

### Bounding box area distribution
![Box area](https://github.com/IzaKam13/Portfolio-4_Data_Annotation_Looker-Studio_Python/blob/main/reports/figures/bbox_area.png)

### Objects per image
![Objects per image](https://github.com/IzaKam13/Portfolio-4_Data_Annotation_Looker-Studio_Python/blob/main/reports/figures/objects_per_image.png)

## Exports
- [YOLO format](https://github.com/IzaKam13/Portfolio-4_Data_Annotation_Looker-Studio_Python/blob/main/exports/annotation-coffee-yolo.zip)
- [COCO format](https://github.com/IzaKam13/Portfolio-4_Data_Annotation_Looker-Studio_Python/blob/main/exports/annotation-coffee-coco.zip)
