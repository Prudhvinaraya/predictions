# predictions
I am going to take some real world problems and solve using AI i.e by Predictions made by my Machine Learning algorithms
#

****BreastCancerDetectionusing Logisitic regression****

Here in the detection of Breast cancer i took a dataset from the kaggle and analyzed the parameters which are responsible for the detection and classifcation into malignant (cancerous) or benign(non cancerous)
I started with the logistic regression algorithm which i imported from sklearn.linear_model
I ended up with an accuracy of  **0.631578947368421** when the training data is 20% of input data
  **Results:**
  Accuracy=0.631578947368421,training_Data=20% of input data
  Accuracy=0.7017543859649122,training_Data=30% of input data
  Accuracy=0.5964912280701754,training_Data=40% of input data
  so i can conclude that the logistic regression model can classify the given patinets record into malignant (cancerous) or benign(non cancerous) with good accuracy when the training data=30% of input data

 ****Red_wine_quality_prediction_using_DeepNN****
  The two datasets are related to red and white variants of the Portuguese "Vinho Verde" wine. For more details, consult the reference [Cortez et al., 2009]. Due to privacy and logistic issues, only physicochemical (inputs) and sensory (the output) variables are available (e.g. there is no data about grape types, wine brand, wine selling price, etc.).
  The Dataset can be viewed as both classification and regression Tasks.The Dataset contains different parameters/features like fixed acidity ,Volatile Acidity,Citric Acid,residual sugar,chlorides,free sulfur dioxide,total sulfur dioxide ,denisty,pH,sulphates ,alcohol and the ouput Feature/label is Quality (which ranges from 0 to 10)
  I used Deep Neural Nets for building the model which can understand the underlying patterns existing within the data.
  Achieved an **loss: 0.0762 - val_loss: 0.0729**
  
  
