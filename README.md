# lab10-team10
lab10-team10 created by GitHub Classroom
1. Yun-Ting
2. Ben
3. Olivia

Exercise One
1. What programming language was used in this tutorial? 
Javascript
2. What were the keys and values in the hello-world sample test event template? 
{Key1: value1, key2,:value2, key3:value3}
3. What can you use if you want to automate the creation and cleanup of lambda function, log groups and roles? 
You can automate the creation and cleanip of functions, log groups, and roles with AWS Cloudformation and the AWS Command Line Interface (ASW CLI). Select Function, choose Actions, Delete. Go to log groups page, select the group and action then delete it. Open Roles page, choose the role, delete it. 

Exercise Two
1. Which line in the function code tries to retrieve the content type of the object? 
print("CONTENT TYPE: " + response['ContentType'])
2. In the test event JSON, what information do you see about the S3 bucket?
"s3": {
        "s3SchemaVersion": "1.0",
        "configurationId": "testConfigRule",
        "bucket": {
          "name": "221lab10",
          "ownerIdentity": {
            "principalId": "EXAMPLE"
          },
          "arn": "arn:aws:s3:::221lab10"
        },
        "object": {
          "key": "URI.png",
          "size": 1024,
          "eTag": "0123456789abcdef0123456789abcdef",
          "sequencer": "0A1B2C3D4E5F678901"
        }
      }
      
3. What information do you see in the Execution Results tab after running test? 
Error, access denied if the bucket name and keys are not updated OR
Response
"image/png"

Function Logs
START RequestId: dd8c96df-5324-4f7a-ba57-89aa881fa602 Version: $LATEST
CONTENT TYPE: image/png
END RequestId: dd8c96df-5324-4f7a-ba57-89aa881fa602
REPORT RequestId: dd8c96df-5324-4f7a-ba57-89aa881fa602	Duration: 158.36 ms	Billed Duration: 159 ms	Memory Size: 128 MB	Max Memory Used: 83 MB

Request ID
dd8c96df-5324-4f7a-ba57-89aa881fa602
