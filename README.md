# Flood-Forecasting-

Flood Forecasting By Using Machine Learning
In this project we are using various machine learning algorithm to predict or forecast flood situation as this is a natural calamity which can cause huge loss of lives and financial assets. Timely and accurate prediction of future floods can help in reduce such loss and to predict flood accurately we have evaluated performance various machine learning algorithms such as SVM, Logistic Regression, MLP and KNN. In all algorithms MLP is giving best performance and to implement this project we have used below flood dataset from KAGGLE website.
 <img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/b40b9647-7b7e-4a1d-b813-ad9988f9d453" />

In above dataset first row contains dataset column names and remaining rows contains dataset values. In each row we have monthly and annual rainfall and based on that we have class label as YES (flood occur) and NO (no flood occur). So by using above dataset we will train all algorithms and evaluate their performance in terms of accuracy, precision, recall, FSOCRE, sensitivity and specificity.
To predict flood we are using below test data 
 <img width="602" height="338" alt="image" src="https://github.com/user-attachments/assets/d1358ae0-d8b6-4b71-9a09-ffb4c255253a" />

In above test data we have monthly and annually rainfall without flood label and when we apply this dataset on MLP algorithm then it will predict flood will occur or not.
To implement this project we have designed following modules
1)	New User Signup Here: using this module we will allow user to signup with the application
2)	User Login: using this module we will allow user to login to application
3)	Preprocess Dataset: using this module we will read flood dataset and then remove missing values and then normalize dataset values and then split dataset into train and test where application use 80% dataset for training and 20% for testing
4)	Run Machine Learning Algorithms: using this module we will train all 4 machine learning algorithms such as SVM, Logistic Regression, KNN and MLP and calculate prediction accuracy on test data
5)	Forecast Flood: using this module we will upload test data and then MLP will predict flood from that test data 
To run project double click on ‘run.bat’ file to start python DJANGO web server and get below output
 

In above screen python DJANGO server started and now open browser and enter URL as http://127.0.0.1:8000/index.html and press enter key to get below page
 <img width="602" height="338" alt="image" src="https://github.com/user-attachments/assets/af8b1964-13c5-4e4e-b689-84252faffc94" />

In above screen click on ‘New User Signup Here’ link to get below page
 <img width="602" height="338" alt="image" src="https://github.com/user-attachments/assets/705b877a-5e64-4def-b642-60086b975582" />

In above screen user is signing up and then click on ‘Submit’ button to complete signup and get below output
 <img width="602" height="338" alt="image" src="https://github.com/user-attachments/assets/5870389f-e07e-4147-b59c-50112b0c502d" />

In above screen signup process completed and now click on ‘User Login’ link to get below login screen
 <img width="602" height="338" alt="image" src="https://github.com/user-attachments/assets/837d5907-b2ed-413e-b90b-9010875e72e1" />

In above screen user is login and after login will get below output
 <img width="602" height="338" alt="image" src="https://github.com/user-attachments/assets/de00374d-5061-4e26-9b36-163b236a41ed" />

In above screen click on ‘Preprocess Dataset’ link to load and process dataset and get below output
 <img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/b63f6ce9-7b93-4fe4-bdda-7081c60b6f20" />

In above screen dataset processing completed and in graph x-axis represents labels as 0 (no flood) and 1 (flood) and y-axis represents number of records in that label and now close above graph to get below output. By using label encoding processing technique we have converted YES and NO to 0 and 1 as machine learning algorithms accept only numeric data
 <img width="602" height="338" alt="image" src="https://github.com/user-attachments/assets/6beb927c-a5ea-449d-8702-84e384bc26a9" />

In above screen entire dataset process and loaded and now click on ‘Run Machine Learning Algorithms’ link to train all algorithms and get below output
 <img width="602" height="338" alt="image" src="https://github.com/user-attachments/assets/a710c32f-fb5a-4446-98f2-399af880bcd5" />

In above screen in tabular format we can see in all algorithms MLP got highest accuracy as 100% and for each run this accuracy may vary from 95 to 100%. Now algorithms are trained and now click on ‘Forest Flood’ link to get below screen
 <img width="602" height="338" alt="image" src="https://github.com/user-attachments/assets/549e3670-3c2d-4a03-8826-630073a0f7c0" />

In above screen select and upload ‘testData.csv’ file and then click on ‘Open’ and ‘Submit’ button to load test data and get prediction output like below screen. This testData.csv is available inside ‘Dataset’ folder
 <img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/83a57d64-27fe-4437-a9f3-b8fd7d1cf8f7" />

In above screen in first column we can see the Rainfall monthly and annually test data and in last column we can see prediction output as ‘Flood May Occur’ in red colour and ‘No Flood Occur’ in green colour.


 
 
   
