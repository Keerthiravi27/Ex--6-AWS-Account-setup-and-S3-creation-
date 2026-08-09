# Ex--6-AWS-Account-setup-and-S3-creation-

# Introduction

In this lab, we are going to be introduced to one of the famous Cloud Service providers, Amazon Web Services (AWS). We will work on Amazon Simple Storage Service (S3), which provides storage through web service interfaces (REST, SOAP, and BitTorrent). In S3, the data is stored in the form of buckets. Buckets serve as root folders where we can add, create, or upload files and folders. We can create multiple buckets for different purposes, and each bucket can have different access control policies.

# Objectives

Create a Bucket in Amazon S3.

Add Objects (files and folders) to the bucket.

Access, move, download, and delete the objects.

Delete the Bucket.

# Illustration

Step 1: Choose S3 Service

Choose the S3 service from the list of services provided by AWS.

<img width="887" height="468" alt="image" src="https://github.com/user-attachments/assets/87f59116-1e33-447b-b997-df1ad08493c2" />


Step 2: Create a Unique Bucket

After selecting the S3 service, click on the "Create Bucket" button on the page. The bucket name must be unique, contain no uppercase letters, and have no special characters. If you enter any of these, an error will display, preventing the bucket from being created.
<img width="887" height="425" alt="image" src="https://github.com/user-attachments/assets/7d379058-4afa-4287-9d32-76d6c951c360" />

<img width="887" height="467" alt="image" src="https://github.com/user-attachments/assets/7cd3da46-3ed9-4650-9d5c-e1712fd383cc" />

<img width="885" height="467" alt="image" src="https://github.com/user-attachments/assets/93ecca7a-6004-4ef1-8cd0-04c04b848a55" />

<img width="1035" height="543" alt="image" src="https://github.com/user-attachments/assets/7dab65d4-a272-43a5-83ca-4d0e77049c9f" />

<img width="992" height="518" alt="image" src="https://github.com/user-attachments/assets/9eb9dd32-64a4-4690-8f57-064281fa26d5" />


For region selection, choose a region from the available list. It is recommended to select a region nearby your location for higher availability. In this lab, I selected Sydney, as it is near my country, New Zealand. Remember to provide a unique bucket name with no special characters or uppercase letters.

Step 3: Upload Files to the Bucket

Now, I have uploaded some files into the bucket I just created. There are no restrictions on uploading file types, but the size of each file must be less than 5 terabytes.

<img width="1032" height="522" alt="image" src="https://github.com/user-attachments/assets/e2e5e38c-3b8f-446f-8273-0dd9967183b7" />

<img width="465" height="402" alt="image" src="https://github.com/user-attachments/assets/72b237e2-4ad8-4eab-8026-1d4ba47cfae9" />


You can upload files of any extension, folders, and subfolders. The images below explain that you can drag and drop files or select them from your computer. After uploading a file, you can download, cut, copy, make it public, rename, or delete it. Making a file public means everyone can access it, and you will receive a link (e.g., https://s3-ap-southeast-2.amazonaws.com/...) to share it.

<img width="1031" height="451" alt="image" src="https://github.com/user-attachments/assets/256142cc-efff-4d51-9a1b-eb33c828591b" />


<img width="1036" height="486" alt="image" src="https://github.com/user-attachments/assets/dab42ac7-a38c-42ab-ac77-b83eb3897b7d" />

Step 4: Upload a Folder

You can also upload a folder to the bucket. If your local folder contains subfolders and data, all data inside the parent folder will be uploaded. The images below show how to upload a folder by dragging and dropping or browsing.

<img width="883" height="351" alt="image" src="https://github.com/user-attachments/assets/845c7e8a-98fe-4010-b73f-cf5fc29c1cb2" />



Step 5: Delete the Bucket
To delete a bucket, you must retype the bucket name. This policy is implemented by Amazon to confirm your action because deleting a bucket can remove large amounts of data.

<img width="350" height="357" alt="image" src="https://github.com/user-attachments/assets/c09c31e3-eaa0-4922-9083-7f8bc99fbe88" />

<img width="1041" height="435" alt="image" src="https://github.com/user-attachments/assets/e9f454f6-3c8b-4aee-ad36-0bcf06b13c72" />


# Result

Successfully created, managed, and deleted an S3 bucket on AWS, demonstrating the ability to upload, access, and control objects within Amazon S3.
