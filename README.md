# S3select
S3 select lambda function to extract subset of data from object and upload to S3 where you want to store the data/results. 

Amazon Simple Storage Service (S3) stores data for millions of applications used by market leaders in every industry. Many of these customers also use Amazon Glacier for secure, durable, and extremely low-cost archival storage. With S3, I can store as many objects as I want and individual objects can be as large as 5 terabytes. Data in object storage have traditionally been accessed as a whole entities, meaning when you ask for a 5 gigabyte object you get all 5 gigabytes. It’s the nature of object storage. Today we’re challenging that paradigm by announcing two new capabilities for S3 and Glacier that allow you to use simple SQL expressions to pull out only the bytes you need from those objects. This fundamentally enhances virtually every application that accesses objects in S3 or Glacier.

## S3 Select
S3 Select, launching in preview now generally available, enables applications to retrieve only a subset of data from an object by using simple SQL expressions. By using S3 Select to retrieve only the data needed by your application, you can achieve drastic performance increases – in many cases you can get as much as a 400% improvement.

### Reference: https://aws.amazon.com/blogs/aws/s3-glacier-select/
