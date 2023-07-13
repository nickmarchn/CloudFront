# CloudFront
This is a cloudfront project I built using the materials I got from a aws course from https://learn.cantrill.io/. I built this out before taking my aws solutions architect certification so I could get hands on experience. 
I didn't run into any issues with this project as it was straight forward. My curiosity did get the best of me and I gathered photos of pets from family and friends and friends, uploaded them to the s3 bucket and played around with the HTML. 


AWS S3,Cloudfront, Route 53,  ACM Project:
Uploaded an S3 bucket with html to create a static website 
Used Cloudfront to allow this website to enable HTTP and HTTPS
This will also enable users to access the website through edge locations
Set up an invalidation for a situation where photos are uploaded frequently
Added a cloud certificate to the distribution and then pointed route 53 to my cloudfront distribution 
