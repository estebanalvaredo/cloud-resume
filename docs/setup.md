# Setup – Cloud Resume (MVP)

## Objective
Deploy a static personal website (Cloud Resume) using AWS S3, CloudFront, ACM and a custom domain.

---

## Section 1 – Steps Taken (Initial Deployment to S3)

1. Created GitHub repository cloud-resume.
2. Added /website/index.html and /website/styles.css.
3. Created S3 bucket cloud-estebanalvaredo-com.
4. Enabled Static Website Hosting and uploaded:
   - index.html
   - styles.css
5. Tested public endpoint:  
   http://cloud-estebanalvaredo-com.s3-website-eu-west-1.amazonaws.com

### Evidence – Section 1

- 01-github-repo.png
- 02-local-index.png
- 03-github-files.png
- 04-local-preview.png
- 05-s3-bucket.png
- 06-s3-website.png
- 07-docs-setup.png

---

## Section 2 – Improving HTML Structure + SEO Meta Tags

1. Edited index.html locally with better structure and meta tags.
2. Added meta tags for SEO, responsiveness, author info.
3. Committed the changes to GitHub.
4. Uploaded updated files to the S3 bucket.
5. Verified the updated site rendered correctly.

### Evidence – Section 2

- 08-meta-tags.png
- 09-git-commit-push.png
- 10-s3-upload-updated.png
- 11-updated-site-browser.png

---

## Section 3 – Frontend Redesign (HTML + CSS)

1. Improved page layout and typography.
2. Tested new design locally.
3. Added favicon and updated the HTML header.
4. Committed changes and re-uploaded to S3.
5. Verified visual redesign in browser.

### Evidence – Section 3

- 12-docs-section-2.png
- 13-html-css-local.png
- 14-git-redesign-commit.png
- 15-s3-upload-redesign.png
- 16-browser-redesign.png
- 18-favicon-html.png

---

## Section 4 – CloudFront Distribution + HTTPS with ACM

1. Created a CloudFront distribution pointing to the S3 static site.
2. Requested ACM certificate for the custom subdomain:
   cloud.estebanalvaredo.com
3. Added DNS validation CNAME in the domain registrar.
4. Certificate issued and attached to CloudFront.
5. Forced HTTPS redirection.
6. Confirmed distribution status as “Deployed”.

### Evidence – Section 4

- 19-cloudfront-create.png
- 20-acm-request.png
- 21-domain-dns-validation-registrar.png
- 22-acm-issued.png
- 23-subdomain-route-settings.png

---

## Section 5 – Domain Routing (DNS → CloudFront)

1. Added CNAME record in registrar for:
   - Host: cloud.estebanalvaredo.com
   - Value: d1epjl4mv6xv0j.cloudfront.net
2. Verified DNS propagation.
3. Website fully accessible at:
   https://cloud.estebanalvaredo.com

### Evidence – Section 5

- 24-dns-cname-added.png
- 25-final-site-https.png
- 26-ssl-browser-details.png

---

## Full Project Documentation

See the full project write-up here:  
[DOCUMENTATION.md](DOCUMENTATION.md)