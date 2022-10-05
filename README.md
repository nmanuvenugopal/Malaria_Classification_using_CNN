# Malaria_Classification_using_CNN

1. Since the image is too large, I haven't uploaded the image, instead done the folder Mapping

2. Proprocessed the image with data augmentation. Important point to note while apply ImageGenerator to the testing dataset is we should make Shuffle to False.
![image](https://user-images.githubusercontent.com/99719105/194032170-12d36c60-67cc-43df-9c8c-cdaf8436725d.png)

3. Build a 3 convolutional layer model. Added Dropout and EarlyStopping to avoid overfitting.
![image](https://user-images.githubusercontent.com/99719105/194032666-f952cc67-c516-4e68-adf1-bf51a83f90a9.png)

4. Evaluated the performance of the model usind various plots and classification report.
![image](https://user-images.githubusercontent.com/99719105/194032984-f6094253-6f3d-45cd-8620-95247bdf99f0.png)
![image](https://user-images.githubusercontent.com/99719105/194033063-bcbcf179-3fa1-47c8-a535-91d789a02e85.png)
![image](https://user-images.githubusercontent.com/99719105/194033157-ed15ec19-5457-4150-b143-dce2f307c08b.png)
![image](https://user-images.githubusercontent.com/99719105/194033235-fc675c0b-0596-45e5-bd31-af98f9c8db65.png)
