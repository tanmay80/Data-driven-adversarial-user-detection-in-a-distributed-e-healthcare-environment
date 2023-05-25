-Language Used
 Python 3

-Editor Used
 Google Colab

-To Create the Pre-Processed File, Follow the Below Steps:-
  1) Open Google Colab or any other notebook( Recommended: Google Colab)

  2) Upload the dataset(dataset.csv) file in google drive(While uploading the file on google drive, directly upload the file in google drive without changing the name and do not put the file in any folder). "diab_clea_version.csv" 

  3)After uploading, open the Data_Preprocessing.ipynb file in the notebook and fire the run-all command(For Google Colab command is "Ctrl+F9" for run all) 

  4)After Step-3 completion, you will get four files (Named:y_train.npy,y_test.npy,train_data.npy,test_data.npy)



- Running of NS_Project file

1)Upload four files (Named:y_train.npy,y_test.npy,train_data.npy,test_data.npy) on google drive(While uploading do not change the name and do not put in any folder)

2)Open Finding_Anomaly.ipynb file in python notebook(Recommended: Google Colab)

3)After Uploading fire run-all command(For Google Colab command is "Ctrl+F9" for run all).

4) After Running, need to enter the below details on the run time
	1) Enter the Client number (Enter the number of the Client whose data you want to forge)
	2) Enter the Percentage Of Data You Want To Manipulate




- Output

After Completion of running, you will be able to see the below results.
1)Accuracy Before Changing the Data
2)Result of Clusters, Euclidean Distance, Manhattan Distance
3)Result of the weighted average of all three methods
4)Accuracy After Changing the Data
5)Accuracy After Dropping the Malicious Client


-Note 
We have considered 10 Users/Clients for the simulation. 


