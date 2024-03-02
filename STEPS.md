# **A project using AWS Services Amazon S3 and Quicksight**

In this project, you'll learn how to create visualizations from a large dataset using Amazon S3 and Amazon Quicksight. We'll be working with a dataset of Top 50 best selling books best-selling products on Amazon.com.

### **Step #1: Download the Dataset**
- Navigate to [Dataset Visualization using AWS S3-Quicksight](https://github.com/Sharang-747/AWSProjects/tree/main/Dataset%20Visualization%20using%20AWS%20S3-Quicksight) to download the "Amazon Bestseller Dataset" CSV file and the "manifest.json" file.
- Click on each file and the select "raw" with Ctrl+S or "download icon" to save both files onto your computer.

### **Step #2: Store the Dataset in Amazon S3**
- Open the Amazon S3 console and click "Create Bucket."
- Name the bucket (e.g., "sharang-amazon-project") you can name it anything you like "but name the s3 bucket using lowercase letters" and keep the settings as default.
- Update the "manifest.json" and then add the bucket name where it is mentioned "bucket-name".
- Now upload the .CSV file and the "manifest.json" file into the bucket.
- Replace the URI in the "manifest.json" file with the S3 URL of your dataset.

### **Step #3: Connect S3 Bucket with Amazon Quicksight**
- Open the AWS management console and navigate to Amazon Quicksight.
- Sign up for a free trial of the Enterprise edition if you don't have an account.
- Select Amazon S3 and tick the box for the S3 bucket you created.
- Enter the link S3-URI to your "manifest.json" file and connect to Quicksight.
- Select "interactive sheet" to start creating visualizations.

### **Step #4: Create Visualizations**
- Drag fields into the graph to create visualizations (e.g., Most popular Authors).
- Sort, filter, and customize the graphs as desired.
- Experiment with different types of graphs like bar charts, pie charts, line graphs, etc.

### **Project Completion Time**
- Approximately 1 hour, depending on the complexity of the visualizations.
