# techops-recruitment

The purpose of this interview is for you to demonstrate technical abilities handling tasks in the cloud as well as some level of coding abilities.

## Question 1:

You are required to create a very small API that can help a train service manage its trains and stations. This is only to get an application to be deployed in AWS on the exercice 2. You are free to use any framework, API generators. You will need a database for this application, it can be a file(raw file or sqlite), a real database(rdbms or nosql), it can be embedded(h2 or hsqldb).

		
| HTTP verb |	Description |:	Action |
|:----------|---------------|:---------|
| POST	| /v1/train (details as JSON body) | Create |
| POST	| /v1/station (details as JSON body) |	Create |
| GET	 |/v1/train/id	| Read | 
| GET	| /v1/station/id | 	Read |


## Question 2:

With the application created in the first exercice, you will have to deploy the application in High Availability with the cloud service of your choice. ECS or EC2, no litesail, no aws amplify. You are required to create manually a VPC with 3 public subnet and 2 private subnets.

when you are done , kindly provide us with the endpoint so we can create a temporary domain to point to you like <yourname>.<ourdomain>.<ltd>

The AWS IAM will be provided to you via your email
