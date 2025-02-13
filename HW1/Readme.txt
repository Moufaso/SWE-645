HW1 Documentation
Saman Hosseini

S3 setup:
1. Created a bucket named “shossei-swe645-hw1”.
2. Unblocked public access.
3. Enabled S3 static website hosting.
4. Added bucket policy for web access.
5. Uploaded my homepage index and error files inside the bucket.

EC2 setup:
1. Created EC2 instance with Amazon Linux image.
2. Updated the instance with “yum update -y.”
3. Installed Apache service with “yum install httpd -y”.
4. Enabled the Apache service with “systemctl enable httpd”.
5. Started the service with “systemctl start httpd”.
6. Uploaded the student survey form files to SWE-645 repository on github.
6. Cloned my SWE-645 repository inside “/var/www/html” directory.

Part 1 – Homepage
. S3 URL: http://shossei-swe645-hw1.s3-website-us-east-1.amazonaws.com
Part 2- Student Survey Form
. EC2 URL: http://3.88.107.109/SWE-645/HW1/Student-Survey/