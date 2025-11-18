# Setup - Cloud Resume (MVP)

## Objective
Deploy a static website with my CV to S3.

## Steps Taken
1. Create GitHub repo 'cloud-resume'.
2. Add 'website/index.html' and 'website/styles.css'.
3. Create S3 bucket 'cloud-estebanalvaredo-com'.
4. Enable Static Website Hosting and upload 'index.html' and 'styles.css'.
5. Test public endpoint: http://cloud-estebanalvaredo-com.s3-website-eu-west-1.amazonaws.com/

## Evidence
- Screenshots:
  - 01-github-repo.png
  - 02-local-index.png
  - 03-github-files.png
  - 04-local-preview.png
  - 05-s3-bucket.png
  - 06-s3-website.png

## Next Steps (priority)
- Add CloudFront + ACM for HTTPS.
- Automate deploy with GitHub Actions (push → deploy to S3).
- Create README with elevator pitch and link to the site.