# Taxi_fare_prediction_machinehack_challange
It is a annual machine learnign challange hosted by machinehack to demonstrate the machine learning skills.

Aim: To predict the taxi fare.
Advantages:
    *The model can be used by online service providers like uber,Ola to make customer understand the taxi fare.
    *customer interactive interface
    
Pipeline steps followed.
  1. import the libraries: pandas ,numpy,sklearn,pickle
  2. read the data
  3. EDA
      check for null data
      check for data redundancy
      outlier handling --using IQR
      handling correlated features----use of corr(),vif     
      data visualization
  4. Model selection and training
     for now 3 model are used.
     after training, those are tested on test data and best model is selected.
 5. Hyper parameter tuning of best model.
 6. making the prediction on test data
 7. create submission file
