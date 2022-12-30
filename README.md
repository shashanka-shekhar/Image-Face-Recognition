# ImageFaceRecognition


Description :

This project extracts face from an image and then predicts to which one out of four celebrities the image belong to.

Dataset :

So the data contain around 100 images of each celebrity namely Kobe Bryant, Kane Williamson, Maria Sharapova, and Cristiano Ronaldo.

Languages and libraries:

This project uses python3, tensorflow, keras, PIL, numpy, pandas, mtcnn, os in kaggle jupyter notebook environment.



Model used :

 1.Pre-trained Facenet model is used for extracting features followed by a linear SVC for classification.
 
 2.MTCNN model was used to extract faces from images.
