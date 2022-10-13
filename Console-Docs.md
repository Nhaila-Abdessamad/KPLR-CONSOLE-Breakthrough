> The Following is the documentation of the kplr console.


## Overall Architecture:


## AWS Lambda Functions:


## Database:
- We used aws RDS with postgres as a runtime.


## The UI Components:


## The Link between UI and Lambda Functions:
- We used aws SQS(Simple Queue Servise) as the link between 
- Each Lambda Function has its own SQS linked to it as a Trigger


## AWS Lambda Functions: