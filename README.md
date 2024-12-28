# Lambda-to-take-snapshot-of-EBS

## Overview:
In this we are gonna take the snapshots of each and every ebs, no matter their ec2 in other regions or in same regions snapshot taken is compulsory.

## Steps:

### 1) Search lambda function and create a function.

![Screenshot (63)](https://github.com/user-attachments/assets/db59d524-7632-4fb0-b6e0-639cff5666bd)
![Screenshot (64)](https://github.com/user-attachments/assets/c076d9df-d974-4a86-ace3-711fead8dea6)

### 2) ADD Trigger in which case the something happens in S3 like images uploaded in the images folder they will send alert to destination.

![Screenshot (65)](https://github.com/user-attachments/assets/f8002684-c3c3-46e1-b83d-125b9cdb152c)
![Screenshot (66)](https://github.com/user-attachments/assets/263dd73e-4a28-4409-a4ea-93b84d4abd10)
![Screenshot (68)](https://github.com/user-attachments/assets/16eb4851-30e6-4538-b24c-ea86e29c0f93)

### 3) Adding Destination for the receive alert message as soon as possible.

![Screenshot (69)](https://github.com/user-attachments/assets/60a35e1f-8a24-436b-9b8f-a42070182084)
![Screenshot (70)](https://github.com/user-attachments/assets/699acd54-c174-4354-afb3-ac71ad556656)

### 4) Add a images in the images of the S3 bucket.

![Screenshot (72)](https://github.com/user-attachments/assets/ce265615-e666-4367-8136-49734a5bf18d)
![Screenshot (71)](https://github.com/user-attachments/assets/fef4261e-8c54-4dcb-a0a6-0ab26d29d13a)

## Result: As a image uploaded in the folder alert received in my mailbox.

![Screenshot (79)](https://github.com/user-attachments/assets/f7d3bed1-471b-49c7-83ff-80b77cbdc72d)
