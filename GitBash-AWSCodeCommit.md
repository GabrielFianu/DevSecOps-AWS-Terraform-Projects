# Creating AWS CodeCommit Respository and connecting it to Gitbash


## Introduction

In this exercise, I will create a new codecommit repository and connect GitBash to the repository. 
Clone the repository onto my local machine so that I CAN push files from my local machine to the codecommit repository, 
and also pull files from codecommit to the local machine.

---


### Step 1
Install the GitBash on your local machine if you don't have it


### Step 2: Create New AWS Codecommit Repository

a. On the AWS management console, search for CodeCommit and open it.

b. Click **Getting Started** on the left pane

c. Click **Create Repository**.

d. Type the name of the repository and click create to create the new repository.


### Step 3: Create an IAM user with CodeCommit Policy permissions and generate security credentials. 

Refer to the earlier exercise to create an IAM user and add AWS CodeCommit Full Access Policy

a. Go to the IAM user you have created and click on the **Security Credentials** .

b. Under HTTPS Git Credentials for AWS CodeCommit, click **generate credentials**.

c. Select **Download Credentials**.


### Step 4: Create a folder where you want to clone the CodeCommit Repository

a. Create a folder and open it.

b. Press the **Shift key** and Right-click at the same time, choose **GitBash Here**.



### Step 5: Copy the url of the CodeCommit Repository you just created.

a. Go back to the CodeCommit and click on the name of the repo.

b. Click Clone the URL and choose clone HTTPS.



### Step 6: Clone the CodeCommit Repository

a. In Gitbash, type:

```
git clone 
```
and paste the url after a space. Hit Enter key.

b. Enter your security details when prompted. You have just cloned your CodeCommit Repository.


### Step 7: Push a downloaded file on your local machine to your Codecommit repo.

a. Download a file from, say GitHub and copy the file to the repo on your local machine.

b. Go to GitBash and cd into the repo

c. Type the git status to see the files in the repo

```
git status
```

d. Type git add and *

```
git add *
```

e. Type git commit -m "message here"

```
git commit -m "Added file"
```

f. Type git push

```
git push
```

g. Go back to CodeCommit repo and click on it. Make sure the right branch is selected.

You will see the file you created there.

---


### Screenshots from exercises

![Image](https://github.com/user-attachments/assets/aa11464d-09f5-4e4d-9f96-37285f09fe73)


![Image](https://github.com/user-attachments/assets/e6d376f8-b86d-44d4-91b5-ccc9aa510626)


![Image](https://github.com/user-attachments/assets/7310734f-bd91-4381-b72a-64a0ac9aee9b)


![Image](https://github.com/user-attachments/assets/b7c41cd9-9a6e-4be6-bba0-e047906e3ef2)


<img width="1366" height="181" alt="Image" src="https://github.com/user-attachments/assets/91e4e92f-f8f0-404c-951e-2fb558431d91" />


<img width="927" height="480" alt="Image" src="https://github.com/user-attachments/assets/fff62a89-e051-402a-a812-932d425ce95f" />


![Image](https://github.com/user-attachments/assets/7e8ed9d9-03c6-40c1-a279-31e1f214ebae)


<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/8bf398c7-4bc0-4254-8bbd-5e3125ed674d" />


<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/62a4ab2c-2a69-480f-8ef6-ea8e047da83f" />


<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/8fdbee74-31ea-4f15-ba88-92cc16de2449" />


<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/8a352544-a133-4b13-8566-6153e8170011" />


<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/1144863c-2f4d-41cc-8f12-f8d47443b494" />


<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/89dff304-a9f0-4a7b-9b2f-075f624b3b69" />


![Image](https://github.com/user-attachments/assets/0e886b19-4a69-42a8-b205-5f07c9949996)


![Image](https://github.com/user-attachments/assets/8ee6f384-6b88-4de1-b70d-c314a5c66f74)


![Image](https://github.com/user-attachments/assets/6aa722f4-95a7-4ed2-b39c-f25c5458b363)


![Image](https://github.com/user-attachments/assets/3a9652f2-6592-42db-a491-c3a41af370ed)


<img width="913" height="369" alt="Image" src="https://github.com/user-attachments/assets/6142a678-6d03-448e-827a-aab9d25683d4" />


<img width="1366" height="181" alt="Image" src="https://github.com/user-attachments/assets/a30d37b2-74e7-4c9d-8d52-695895057e09" />


![Image](https://github.com/user-attachments/assets/f4c6eb99-9efc-46ad-b864-894f79089e4c)


![Image](https://github.com/user-attachments/assets/2884ac4f-490e-46a2-a270-f7b286579881)


![Image](https://github.com/user-attachments/assets/d9105df5-8036-4e4d-878d-03bc4fb33250)


![Image](https://github.com/user-attachments/assets/ed5e55a6-37a8-47e5-b620-930e7ca8ad2b)


![Image](https://github.com/user-attachments/assets/80c510dd-dd38-4021-8eb3-d8f29656c15f)


<img width="752" height="524" alt="Image" src="https://github.com/user-attachments/assets/58f24240-2a84-4b73-bf70-576e64a8fcab" />


![Image](https://github.com/user-attachments/assets/e97bc53a-554f-434d-8188-5150f3678527)


![Image](https://github.com/user-attachments/assets/9f7501d5-4e2b-4be1-b674-75d68fd2f395)


![Image](https://github.com/user-attachments/assets/25f0460d-db8f-41c6-a2c2-4ad44674e1f3)


<img width="1366" height="768" alt="Image" src="https://github.com/user-attachments/assets/7fb44aab-ee4f-407c-ae79-4cc0b9b61785" />


![Image](https://github.com/user-attachments/assets/34ae4168-9911-45a4-841e-8bea8eabe26e)


<img width="1366" height="181" alt="Image" src="https://github.com/user-attachments/assets/c8d6aefa-2fba-4389-8493-a0f7685af489" />


<img width="594" height="648" alt="Image" src="https://github.com/user-attachments/assets/346bd6c5-b8e9-497e-b377-709d79e1f876" />


![Image](https://github.com/user-attachments/assets/cb4afbc6-a6e5-4d9b-ab32-f32c94a2f043)


![Image](https://github.com/user-attachments/assets/a3397233-378d-4925-a466-10faf87977f2)


![Image](https://github.com/user-attachments/assets/23024012-e9da-4941-97ad-64495a34e3d1)


![Image](https://github.com/user-attachments/assets/818908cb-5b7b-4683-ab4f-a7851ee075c5)


![Image](https://github.com/user-attachments/assets/0276d865-40cb-4e5d-9a24-d5c47798e22d)


![Image](https://github.com/user-attachments/assets/ff6bc45c-e1ce-4b6e-80c7-a4e3c7706075)


![Image](https://github.com/user-attachments/assets/4984d51b-5d98-4e48-b2eb-42655ef19802)


![Image](https://github.com/user-attachments/assets/872fae06-9409-4adb-9e19-82206aa66eac)


![Image](https://github.com/user-attachments/assets/d5366539-c74e-4043-8095-5c36a15b1de5)









