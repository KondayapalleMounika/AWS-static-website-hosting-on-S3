# AWS-static-website-hosting-on-S3
To host a static website on Aws S3 Bucket.

*What is meant by static and dynamic websites*

Static website consists of series of HTML and CSS pages which displays same information for all users who are going to access that website.
Dynamic website uses server technologies like PHP and many more to build webpages dynamically and displays unique information for each user.

*Why to host static website on AWS S3.*

To host static websites no need of servers. And S3 hosts only static websites. In S3 there is significant cut in costs because it has no server technology.

   1. Can keep track of deployed website with no maintanence.
   2. Always Virtually available until we delete the bucket.
   3. Cost effective ( No server Costs).

      #it works hello world
      
*How to host static website on AWS S3.*

    1. Create bucket and allow public access for bucket. To make bucket public, need to create bucket policy.
    2. Enable static webhosting on bucket ( properties -> static web hosting) by selecting index.html and error.html documents.
    3. Upload both documents(index and error) on s3 bucket.
    4. we can check by copying object URL and paste in chrome.
