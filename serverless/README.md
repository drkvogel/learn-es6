





app: myapp-dev
tenant: drkvogel

AWS Identity and Access Management (IAM) enables you to manage access to AWS services and resources securely. Using IAM, you can create and manage AWS users and groups, and use permissions to allow and deny their access to AWS resources.

AWS Lambda runs your code on a high-availability compute infrastructure and performs all of the administration of the compute resources, including server and operating system maintenance, capacity provisioning and automatic scaling, code monitoring and logging.

All you need to do is supply your code in one of the languages that AWS Lambda supports (currently Node.js, Java, C#, Go and Python).

### setup

```bash
$ npm i -g serverless
$ serverless login
# Create a serverless function
$ serverless create --template aws-nodejs

[  7:18pm ]  [ kvogel@kvogel-macbook-2018:~/Projects/learn-es6/serverless(master✗) ]
 $ serverless create -t aws-nodejs
Serverless: Generating boilerplate...
 _______                             __
|   _   .-----.----.--.--.-----.----|  .-----.-----.-----.
|   |___|  -__|   _|  |  |  -__|   _|  |  -__|__ --|__ --|
|____   |_____|__|  \___/|_____|__| |__|_____|_____|_____|
|   |   |             The Serverless Application Framework
|       |                           serverless.com, v1.36.1
 -------'

Serverless: Successfully generated boilerplate for template: "aws-nodejs"
Serverless: NOTE: Please update the "service" property in serverless.yml with your service name

# deploy to cloud provider
$ serverless deploy
# Your function is deployed!
$ http://xyz.amazonaws.com/hello-world

```

Serverless Platform Beta v.0.2 July 5th, 2018
Visualize your serverless applications - View the services you've deployed with the Serverless Framework. Inspect configurations, monitor deployment activity and more.
Collaborate with your team - Share your Serverless Framework projects with teammates.
Simplify event-driven architectures - Your account includes access to a hosted Event Gateway, an event router capable of routing event data across cloud accounts, cloud providers, and back-end SaaS solutions.