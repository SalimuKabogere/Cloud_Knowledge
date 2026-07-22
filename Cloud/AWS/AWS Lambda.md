This is an AWS compute that runs your backend code in response to events such as Object updates to S3 buckets etc
Once you upload your code to lambda, the service handles all the capacity, scaling, patching and the admin of the infrastructure to run your code

It provides performance through logs and other metrics that the user can monitor to Amazon Cloud Watch

All you need to do is to write the code
The code you run on AWS lambda is called a lambda function, either upload your code in a zipped file or use the AWS management console

Lambda is a serverless compute service
>>Upload code
>>Set triggers
>>Function runs in response to that trigger

Pay for only the compute you use
The max duration of a lambda function is 15min