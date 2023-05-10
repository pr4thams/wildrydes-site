# Wild Rydes - AWS Serverless Application

Website URL hosted on AWS Amplify ---> [Wild Rydes - Rydes of the Future!](https://main.d2pdbx3gldv4qa.amplifyapp.com/)

## Technologies Used
- AWS Amplify: Hosted the static resources for the web applications from a GitHub repo with CI/CD built in.
- AWS Cognito: Created a user pool to manage users' account. Used SRP to authenticate and generate a set of JSON Web Tokens.
- AWS Lambda: Implemented a Lambda function that holds the CRUD operations and is invoked each time the client requests a unicorn to be sent.
- DynamoDB: Used it to record all the instances that the client selected a unicorn.
