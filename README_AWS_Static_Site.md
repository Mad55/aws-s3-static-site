
# AWS Static Website with Custom Domain + HTTPS

## 🚀 Overview
Deployed a personal static portfolio site using Amazon S3 and hosted it under a custom domain (marionmauriceproject.com) purchased via Namecheap. Secured the website with HTTPS using Amazon CloudFront and AWS Certificate Manager.

## 🌐 Live Demo
🔗 http://marionmauriceproject.com/

## 🧰 AWS Services Used
- Amazon S3 (Static Website Hosting)
- Route 53 (DNS Hosting)
- AWS Certificate Manager (SSL)
- Amazon CloudFront (CDN + HTTPS)
- Namecheap (Domain Registrar)

## 📁 Project Structure
```
aws-s3-static-site/
├── index.html
├── style.css
├── README.md
└── screenshots/
    └── site-live.png
```

## 🛠️ Deployment Steps
1. Hosted static site in an S3 bucket named after the domain.
2. Enabled static website hosting and uploaded `index.html`.
3. Created a Route 53 hosted zone and pointed a Namecheap domain to Route 53 name servers.
4. Set up an A Record Alias to a CloudFront distribution for HTTPS.
5. Issued an SSL certificate using AWS Certificate Manager (ACM).
6. Connected everything using CloudFront to serve the S3 website securely over HTTPS.

## 📸 Screenshots
![Live Site](./screenshots/site-live.png)

## 🧠 Lessons Learned
- End-to-end static site deployment on AWS
- Domain name management and DNS routing via Route 53
- Enabling HTTPS with ACM and CloudFront
- Understanding DNS propagation and bucket permissions

## 🧑‍💻 Author
Marion Maurice Coggins III  
[LinkedIn](https://www.linkedin.com/in/mauricecoggins/)
