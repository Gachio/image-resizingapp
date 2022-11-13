It all starts with AWS Documentation for better understanding.

The function Fn::Join appends a set of values into a single value, separated by the specified delimiter. The delimiter here is ""

The function Ref returns the value of the specified resource. The Ref function here returns the value of ImageRedimBucket.

I use the ImageRedimProfile to pass an IAM role to the EC2 instance in order to have access to the S3 bucket.

