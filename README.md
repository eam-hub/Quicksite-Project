# Visualization With Quicksite
My first project is to showcase data in an S3 by creating dashboards with Amazon Quicksite.
This project was done with the assistance of Lucy Wang's @techwithlucy youtube page.

Quicksight provide us with interactive visualizations and dashboards that we can use to analyze data stored in the cloud. In this project I downloaded a dataset of the 50,000 top selling Amazon products and stored them in an S3 bucket. I then created a Quciksite account and connected the S3 to Quicksite. Quicksite then provided me with a dashboard of the data.

![quicksite drawio (1)](https://github.com/user-attachments/assets/98b705ee-d48b-4386-82e4-824aa146ac63)


## Created an S3 Bucket and Upload the Dataset
the first step was to create an S3 bucket to store the data in. I created a bucket and named it "big-dataproject"

![Capture](https://github.com/user-attachments/assets/636d1786-f0c6-45ce-a50d-0d6d8c116836)


The CSV file that contained the dataset (Amazon-Bestseller-Dataset.csv) was given to us by Lucy's github page. The manifest.json document that will be used later so that Quicksite can access the S3 bucket was also given to us by Lucy's github page. I upload both of these documents to the S3 bucket.

![Capture](https://github.com/user-attachments/assets/adf3fa92-e174-4e72-958b-945e1e688a34)


### Create a Quicksite Account and Attached My S3 bucket
I created a free trial quicksite account and created a new dataset. 
Then click S3 and from here you can upload your manimest.json document to connect to your S3. Enter any name you like under "Data Source Name".
![Capture](https://github.com/user-attachments/assets/ce46392c-b92a-451d-aa47-307b2e7832dd)
![Capture2](https://github.com/user-attachments/assets/ce43e2b3-53ae-4c2f-acbb-274845c7e161)


Drag the field "Brand" located on the left side of the page into the autograph in the middle. your dashboard should appear. 
![Capture3](https://github.com/user-attachments/assets/187a5fa0-0ebe-41bc-9c40-c527641a1c00)


