# Cloud Resume — Static Website on AWS (S3 + CloudFront + ACM)

This project implements a personal static website hosted on Amazon S3, served globally through CloudFront, and secured with a custom domain using ACM-issued SSL certificates.  
All deployment steps and evidence are included below.

---

## Project Structure

cloud-resume/
├── website/
│   ├── index.html
│   ├── styles.css
├── README.md
├── docs/
│   ├── setup.md
│   ├── DOCUMENTATION.md
│   └── images/

---

# 1. GitHub Setup & Local Project Creation

### GitHub repository created  
![GitHub repo](images/01-github-repo.png)

### Local HTML/CSS development  
![Local index](images/02-local-index.png)

### Files uploaded to GitHub  
![GitHub files](images/03-github-files.png)

### Local preview before deployment  
![Local preview](images/04-local-preview.png)

---

# 2. Deploying Website to S3

### S3 bucket created  
![S3 bucket](images/05-s3-bucket.png)

### Website uploaded to bucket  
![S3 website](images/06-s3-website.png)

### Initial project setup documented  
![Docs setup](images/07-docs-setup.png)

---

# 3. Improving HTML/CSS

### Adding <meta> tags  
![Meta tags](images/08-meta-tags.png)

### Git commit & push  
![Git push](images/09-git-commit-push.png)

### Updated version uploaded to S3  
![Upload updated](images/10-s3-upload-updated.png)

### Browser preview after update  
![Updated browser](images/11-updated-site-browser.png)

---

# 4. Website Redesign

### Section reorganized in docs  
![Docs section 2](images/12-docs-section-2.png)

### Testing CSS changes locally  
![CSS local](images/13-html-css-local.png)

### Git commit for redesign  
![Git redesign commit](images/14-git-redesign-commit.png)

### Uploading redesign to S3  
![Upload redesign](images/15-s3-upload-redesign.png)

### New design displayed in browser  
![Browser redesign](images/16-browser-redesign.png)

### Favicon added  
![Favicon HTML](images/18-favicon-html.png)

---

# 5. CloudFront + HTTPS (ACM)

### CloudFront distribution created  
![CloudFront create](images/19-cloudfront-create.png)

### ACM certificate requested  
![ACM request](images/20-acm-request.png)

### ACM DNS validation record  
![DNS validation registrar](images/21-domain-dns-validation-registrar.png)

### ACM certificate issued  
![ACM issued](images/22-acm-issued.png)

### CloudFront root domain routing settings  
![Root routing settings](images/23-subdomain-route-settings.png)

---

# 6. Custom Domain Configuration

### CNAME added at registrar  
![DNS CNAME](images/24-dns-cname-added.png)

---

# 7. Final Result (HTTPS working)

### Website served over HTTPS through CloudFront  
![Final HTTPS](images/25-final-site-https.png)

### Browser SSL certificate details  
![SSL details](images/26-ssl-browser-details.png)

---

# Project Completed

The static website is now:

- Hosted on Amazon S3
- Distributed via CloudFront
- Secured with ACM SSL
- Mapped to a custom domain
- Version-controlled via GitHub

This project establishes a clean, professional foundation for a Cloud Resume.
