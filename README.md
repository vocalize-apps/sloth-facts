# Sloth Facts 
An Alexa skill that gives interesting facts about sloths.

[![Enable This Skill](https://dabuttonfactory.com/button.png?t=Enable+This+Skill&f=Calibri-Bold&ts=24&tc=fff&tshs=1&tshc=000&hp=20&vp=8&c=5&bgt=gradient&bgc=0ff&ebgc=187cd8&shs=1&shc=444&sho=s)](https://www.amazon.com/dp/B07PN3ZJVY/ref=sr_1_3?keywords=sloth+facts&qid=1552429215&s=digital-skills&sr=1-3)

## Usage

> "Alexa, open sloth facts"

> "Tell me a random fact"

> "Tell me a two toed sloth fact"

# :smiley_cat: Installation
You will need to complete the prerequisites below before creating the skill and deploying the fulfillment handler.

## Pre-requisites
In order to get started you will need to create an alexa developer account and an aws account.

* [Alexa Developer](https://developer.amazon.com/alexa)
* [Amazon Web Services (AWS)](https://aws.amazon.com/)

## Setting up Alexa Skill

Simply copy the models under interaction_models into the JSON Editor underneath intents in your alexa developer account. Don't forget to click on save and build model!

For more information read [here](https://developer.amazon.com/docs/devconsole/build-your-skill.html#custom-model).

## Setting up AWS
1. Install [Serverless](https://serverless.com/)
2. Install [serverless-python-requirements](https://www.npmjs.com/package/serverless-python-requirements)
3. `pip install -r requirements.txt`


## Deploy fulfillment handler
You can deploy with your default aws profile

`sls deploy`

Or deploy with a different profile:

`AWS_PROFILE=alexa-user sls deploy`

# Resources
* [Alexa Skills Kit SDK for Python](https://alexa-skills-kit-python-sdk.readthedocs.io/en/latest/index.html)
