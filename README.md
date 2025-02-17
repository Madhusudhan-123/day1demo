[AWS S3&IAM.docx](https://github.com/user-attachments/files/18825830/AWS.S3.IAM.docx)


import boto3
day1session=boto3.Session(region_name='us-east-1')

s3client=day1session.client("s3")
bucket_name="madhuday1456"
s3client.create_bucket(Bucket=bucket_name)
