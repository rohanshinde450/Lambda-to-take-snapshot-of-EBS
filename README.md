# Lambda-to-take-snapshot-of-EBS

## Overview:
In this we are gonna take the snapshots of each and every ebs, no matter their ec2 in other regions or in same regions snapshot taken is compulsory.

## Steps:

### 1) Search lambda function and create a function.

![Screenshot (73)](https://github.com/user-attachments/assets/0e64788a-7fec-437f-bcd8-bad253452f70)

### 2) A Ec2 Lambda Role is created to give full access of Ec2 to Lambda for run the code and take the snapshots of each and every ebs.

![Screenshot (74)](https://github.com/user-attachments/assets/b0a70139-8105-4949-bd6d-a7f11e6ba7fd)
![Screenshot (75)](https://github.com/user-attachments/assets/0239f2f3-d512-40ff-89a4-39fa9add20cc)

### 3) paste the code to write for the take snapshots of ebs and create the test event also deploy the code, if there is an error between deploying the code then add deploying time. 

![Screenshot (76)](https://github.com/user-attachments/assets/15e5fc86-a561-43bf-993a-88eae2e45cf7)
 
### Result:

![Screenshot (77)](https://github.com/user-attachments/assets/51776c13-56d4-4b5a-9568-26dcd1aeef24)
![Screenshot (78)](https://github.com/user-attachments/assets/5f628f0a-1403-4101-921c-678364b71447)
