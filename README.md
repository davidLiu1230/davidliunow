bootstrap:
 - make bootstrap
 - jekyll new my-blog-name
 - s3_website cfg create
 - update s3_website.yml

s3:
 - set up IAM user
 - set up s3 bucket with the correct read permission
 - turn on static web hosting on the bucket

deploy:
 - make upload

write a post:
 - To start a new post, type "make new <POST_NAME>"
