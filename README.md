# Bauns - CloudFormation to set up event notifications for Amazon SES

This repository contains a CloudFormation template, `template.yaml` which creates an SES Configuration Set that can be attached to one or more SES Identities (Email Addresses or Domains).

The SES Configuration Set will send bounce, complaint, delivery and send Notifications to bauns.net via an SNS Topic.


