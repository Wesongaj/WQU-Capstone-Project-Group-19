## WQU-Capstone-Project-Group-19
## Modeling the Benefits of co-location/Proximity hosting to Matching Engines on HFT Using Machine Learning 

* Framework to capture the dynamics of high-frequency limit order books.

  <img src="./Graphs/bse colocation trading arch.png" width="650">
  
#### Overview

In this project I used machine learning methods to capture the high-frequency limit order book dynamics and simple trading strategy to get the P&L outcomes.

* Feature Extractor

  * Auto-Correlation
  
    <img src="./Graphs/79790109-ea9e7980-8353-11ea-97a7-57fd01e1f31c.png" width="650">

  * Normal Distribution
  
    <img src="./Graphs/Normal.png" width="650">
    
    [Note] : [Feature_Selection] (Feature_Selection) 
 
* Learning Model Trainer
  
  *  RandomForestClassifier
  *  ExtraTreesClassifier
  *  AdaBoostClassifier
  *  GradientBoostingClassifier
  *  SVM
  
*  Use best model to predict next 10 seconds

   <img src="./Graphs/.png" width="650">
   
*  Prediction outcome

   <img src="./Graphs/.png" width="650">
   

   
   [Note] : [Model_Selection] (Model_Selection) 

 
