## About the Project
In this project, YOLO was fine-tuned on aerial images of cars, enabling the model to detect vehicles from satellite and drone imagery. This is particularly useful for applications such as parking lot monitoring. To further enhance performance and address issues caused by occlusion in car images, annotated bounding box locations were used to identify object positions in each image. In this case, trees were mapped onto the cars, and the model was further trained to improve detection accuracy under occluded conditions.

## Workflow 
### Annotations 
We labelled the data through VGG online annotator. Exported the annotations as csv format and then converted them csv into YOLO format getting corresponfing .txt file for each image

### Data Augmentation
Performing data augmentation and merging the augmented data with original dataset

### Training YOLO
Laslty training YOLO on our dataset
