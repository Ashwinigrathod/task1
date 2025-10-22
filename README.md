# task1
AWS S3 File Upload and Access Project

## 🎯 Objective
To create an Amazon S3 bucket, upload a file, make it publicly accessible, and view the file using the Object URL.

---

## 🧭 Steps Followed

### 1️⃣ Create an S3 Bucket
- Logged in to the AWS Management Console.
- Searched for *S3* and clicked *Create bucket*.
- Gave a unique name: demo1223444.
- Selected the region: us-east-1.
- *Unblocked public access* by unchecking Block all public access.
- Clicked *Create bucket*.

### 2️⃣ Upload a File
- Opened the created bucket.
- Clicked *Upload → Add files*.
- Selected a local file (e.g., image ).
- Clicked *Upload* to store it in S3.

### 3️⃣ Configure Public Access
- Selected the uploaded file → Clicked *Actions → Make public using ACL*.
- Confirmed that Everyone (public access) had *Read* permission.

### 4️⃣ Access the File via URL
- Copied the *Object URL* displayed in the file details.
- Pasted it into a web browser.
- Successfully accessed the file publicly 🎉

---

## 🖼️ Screenshots
| Step | Description | Screenshot |
|------|--------------|-------------|
| 1 | Bucket creation | ![Bucket Creation](screenshot1.png) |
| 2 | File upload | ![File Upload](screenshot2.png) |
| 3 | Public access setup | ![Permissions](screenshot3.png) |
| 4 | File accessible in browser | ![File URL](screenshot4.png) |

---

## 🧰 AWS Services Used
- *Amazon S3 (Simple Storage Service)*  
- *AWS Management Console*

---

## 💡 Key Learnings
- How to create and configure an Amazon S3 bucket.  
- How to upload and manage objects in S3.  
- How to modify permissions and enable public access.  
- Understanding Object URLs and S3 bucket policies.

---

## 🧹 Cleanup (to avoid charges)
- Deleted the uploaded file after testing.  
- Deleted the S3 bucket to ensure no billing occurs.  

---

## ✅ Project Outcome
Successfully created and accessed a publicly available file using Amazon S3 Object URL.

---

### 👩‍💻 Author
*Ashwini G. Rathod*  
Simplilearn Certified Cloud Architect | AWS & Azure Learner  
📧 [ashwinirathod701@gmail.com]  
🔗 [https://github.com/Ashwinigrathod]
