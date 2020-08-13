# AWS monthly billing slack bot

Send AWS monthy summary billing in a slack channel via webhook.


## Example of message
This is an example of message send in Slack:

<p align="center">
  <img src="https://raw.githubusercontent.com/moroleandro/aws-billing-slackbot/master/assets/example.png" alt="logo" />
</p>
<br>

## Getting Started

### Prerequisites

To perform the project installation you need to have a package manager installed in your environment, such as the following:
* [Yarn](https://yarnpkg.com/pt-BR/)
* [Npm](https://www.npmjs.com)

## Installing process
### Cloning the porject
```
git clone https://github.com/moroleandro/aws-billing-slack.git

cd aws-billing-slack
```

###  Instaling the project
Install project depencencies:

`npm install`

### Configure Slack

Create an [incoming webhook](https://www.slack.com/apps/new/) on slack.

### Deploy
**IMPORTANT:** Configure the [serverless file](./serverless.yml) whith with your provider credentials. You can use this [guide](https://www.serverless.com/framework/docs/providers/aws/guide/credentials#create-an-iam-user-and-access-key). 

Or use Lambda Service 

Deploy the project to your AWS account with the following command:

`npm run deploy -- --slack_url="<slack_webhook_url>"`

## Author
[@moroleandro](https://github.com/moroleandro)
