This is a quick guide to how this personal blog is built&deployed.

static website:
 - gem install jekyll
 - jekyll new my-blog-name
 - gem install s3_website
 - s3_website cfg create
 - update s3_website.yml

s3:
 - set up IAM user
 - set up s3 bucket with the correct read permission
 - turn on static web hosting on the bucket

deploy:
 - jekyll build
 - s3_website push

Voila!

Notes:
 - Might need to install Java to run s3_website
 
