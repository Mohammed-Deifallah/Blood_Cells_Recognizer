# Blood_Cells_Recognizer

# Identifying the type of blood cells from images

![cover](https://drive.google.com/uc?export=view&id=1vCdFIYUiC_dY0vI7IvUtopXy6t-g9VFX)

The diagnosis of blood-based diseases often involves identifying and characterizing patient blood samples.  
So, providing automated methods to detect and classify blood cell subtypes would be a huge benefit and would have important medical applications.

## Data
**Note**: You can find data in the Kaggle competttion linked below

This dataset contains 12,500 augmented images of blood cells (JPEG) with accompanying cell type labels (CSV). 

There are approximately 3,000 images for each of 4 different cell types grouped into 4 different folders (according to cell type).

This dataset is accompanied by an additional dataset containing the original 410 images (pre-augmentation) as well as two additional subtype labels (white blood cells WBC vs red blood cells RBC) and also bounding boxes for each cell in each of these 410 images (JPEG + XML metadata).

### Sample Images

![sample_images](https://github.com/youssef-ahmed/Blood_Cells_Recognizer/blob/master/snapshots/sample.png)

Types of blood cells are :
1. Mononuclear
  - Lymphocyte
  - Monocyte
  - Basophil
2. Polynuclear
  - Eosinophil
  - Neutrophil  

For more information about blood cells and blood cell subtypes, see the following links:
- https://www.ncbi.nlm.nih.gov/books/NBK2263/
- https://www.ncbi.nlm.nih.gov/books/NBK2263/box/A26/?report=objectonly

## References:

Link to Kaggle:  https://www.kaggle.com/paultimothymooney/blood-cells/home
