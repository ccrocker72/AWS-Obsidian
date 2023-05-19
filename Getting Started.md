## Create an AWS Account
email: ccrocker7227@gmail.com
username:ccrocker72
PW: AWSConsole!1

## Create IAM User
Identity and Access Management
go to IAM, create new user, assign group (can create new group name if necessary)
force user to create password on first login.

now log in as IAM User
account ID
656947938563
sign in URL
https://656947938563.signin.aws.amazon.com/console
username
ccrocker
pw
gJ3PJ{)l (generated)
AWSTest!1 (new)

log out then log back in to make sure the new password works

## AWS Region Selector
recommended to run in us-east-1
some services are global, but some are not

## Overbilling Story
Be careful when setting up a service and be aware of spend
example provided was elasticache

## AWS Budgets
can use template to set budget amount, pretty straightforward

## AWS Free Tier
can set billing preferences to get free tier alerts
different services have different "trial" periods in this tier

## Billing Alarm
start by looking up cloudwatch (a collection of services)
Go to Billing tab. Can get 10 free alarms and 1,000 free email notifications each month in the free tiers
fill out metric name, threshold type, condition and value
Set alarm (may need to create new topic)
Click through the menu and create the alarm
