# AWS S3 Static Website Hosting (Simulated)

This project demonstrates how to host a static website using **Amazon S3**.  
Due to account restrictions, this deployment is simulated locally, but all steps provided here can be executed in an AWS Free Tier account.

---

## Project Overview
We create a simple static HTML page (`index.html`) and simulate hosting it on AWS S3.

---

## Steps for Real Deployment

1. **Create an AWS Account**
   - Sign up at [https://aws.amazon.com/free](https://aws.amazon.com/free).
   - Verify with a debit/credit card (no charges for free tier).

2. **Create an S3 Bucket**
   - Go to **S3** service in AWS console.
   - Click **Create Bucket**, give it a unique name, and select a region.
   - Uncheck **Block all public access**.

3. **Upload Files**
   - Open your bucket → Click **Upload** → Select `index.html`.

4. **Enable Static Website Hosting**
   - Go to **Properties** tab of the bucket.
   - Enable **Static website hosting**.
   - Set **Index document** as `index.html`.
   - Save changes.

5. **Access Your Site**
   - AWS will provide a public endpoint like:
     ```
     http://<bucket-name>.s3-website-<region>.amazonaws.com
     ```

---

## Simulated Output
As we cannot deploy to AWS directly, this folder contains:
- `index.html` (Website content)
- `screenshots/` (Placeholder images showing expected AWS console steps)

---

## Learning Outcome
- Understanding AWS S3 static website hosting
- Setting bucket permissions
- Configuring public access
- Managing static assets in the cloud
