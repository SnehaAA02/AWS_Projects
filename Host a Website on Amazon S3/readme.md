# Host a Static Website on Amazon S3  

This project demonstrates how to host a static website using **Amazon S3** 

## 🧩 Project Steps
### Step #1: Create an Amazon S3 Bucket
- Click **Create bucket**
- **Bucket name**: Choose a unique name (e.g., `my-static-website-bucket`)
- **Region**: Select a region close to you
- Select **ACLs enabled (to make all objects in a bucket public)**
- Uncheck **Block all public access**
- Acknowledge the warning (required for public websites)

---

### Step #2: Upload Website Content to Your Bucket
- Upload `index.html` and any required static files (CSS, images) to the S3 bucket.
- Ensure files are uploaded to the root of the bucket.
- Verify that all required website assets are present.

---

### Step #3: Configure a Static Website on Amazon S3
- Open the S3 bucket **Properties** tab.
- Enable **Static website hosting**.
- Set:
  - **Index document**: `index.html`
- Save the configuration.

---

### Step #4: Make Objects in Your S3 Bucket Public
- Update the permissions of objects in bucket to allow public access by using ACL.


<img width="1920" height="731" alt="Bucket" src="https://github.com/user-attachments/assets/7434bbf1-40b6-4c55-8518-c3f891c925d2" />
<img width="1920" height="1042" alt="Website" src="https://github.com/user-attachments/assets/120d622b-a030-4d2b-8db1-b274354079dc" />



