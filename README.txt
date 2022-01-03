Deploy Static Website on AWS

In this project, you will deploy a static website to AWS using S3, CloudFront, and IAM.

The files included are: 

index.html - The Index document for the website.
/img - The background image file for the website.
/vendor - Bootssrap CSS framework, Font, and JavaScript libraries needed for the website to function.
/css - CSS files for the website.

---

Eric Koch's Udacity Cloud DevOps Project 1 - Deploy Static Website on AWS

S3 Bucket Link:             https://udacity-827032113985-project1site.s3.amazonaws.com/index.html
S3 Static Website Link:     http://udacity-827032113985-project1site.s3-website-us-east-1.amazonaws.com/
CloudFront Distro Link:     https://d3gachdqsiqixw.cloudfront.net

You can find the relevant project photos for submission in /project-photos.

The website is accessible by any of the above links. The latter two links redirect to index.html.

It's just a cute little wargame blog website, and I decided against adding a bunch of extra pages.

There's also a little javascript app to count things, with a fancy little css class-
if you hover over the count box, it expands! That was the extent of my creativity for this one :)

Troubleshooting notes:
/js was added to remove web console errors for not having a css js reference, likewise the absence of 
favicon.ico was raising errors.