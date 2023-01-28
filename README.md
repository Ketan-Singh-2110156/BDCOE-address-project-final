# ADRESS-PROJECT-BDCOE

1. This project aims at verifying the address from the dataset as valid and invalid with creating csv files for the earlier mentioned categories.
2. The logic behind veryfying address is that all the addresses must have pincode in integers where no integer can be greater than 9999999999. 
3. The pincode/postalcode cannot contain any string characters and zero values.
4. Various API's are being used in this project to verify locations as on maps. 


## WORKING OF THE PROJECT 

1. Different Dataframes are created dropping null values, zero values. 
2. Mailing Streets, Cities are used as inputs for the API's used in the project. 
3. In the end two files are created , Valid Address and Invalid Address satisfying the requirements. 
4. API's are Created by our own Datasets.

## Dependecies 

1. Pandas(for installing pandas run command "pip install pandas" in terminal).
2. Jupyter Notebook or any pyhton notebook software
 
 ## Steps to run the project
 
 1. Give the address of the file.
 2. Run the Notebook.
 3. we will get a two output CSV files for every country named "Invalid Addresses.csv" and "Valid Addresses.csv".
 
 
## Important Note.
 Please check the names of the given Datasets, they should be named according the following manner
  1. country name => "MailingCountry"
![image](https://user-images.githubusercontent.com/114509252/215261775-d6607327-b9da-4d60-a009-bcd11c1646f6.png)

 2. city name => "MailingCity"
![image](https://user-images.githubusercontent.com/114509252/215261793-3fd82d6a-0346-43cb-baf9-3a060c53744a.png)
3. ZIP address => "Mailing Zip Code"
![image](https://user-images.githubusercontent.com/114509252/215261825-5f5110fb-3b31-4512-8ce1-7087fe3ef321.png)
4. Mailing address => "MailingStreet"
![image](https://user-images.githubusercontent.com/114509252/215261847-c7808f29-fd98-47ca-9c40-aae41ea3d53c.png)
 
