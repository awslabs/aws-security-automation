# aws-security-automation
Collection of scripts and resources for DevSecOps, Security Automation and Automated Incident Response Remediation

## IAM Access Denied Responder

This example solution will setup an automated response to an access denied event that occurs within a CloudTrail event, a Failed authentication attempt to the AWS console, or a Client.UnauthorizedOperation event occurs.

## EC2 Auto Clean Room Forensics

This example solution will take an instance ID from an SNS topic and through a series of AWS Lambda functions co-ordinated by AWS Step Functions will automatically notify, isolate and run basic forensics on the identified instance.  

## CloudTrailRemediation
Demo script to automatically restart CloudTrail. The script have placeholders for forensics etc. to avoid enabling CloudTrail without finding the causing user.

## force-user-mfa
Demo script to automatically create and attach virtual MFA to any newly created IAM user. The user can fetch the MFA Seed themselves using AWS CLI.

***

Copyright 2016 Amazon.com, Inc. or its affiliates. All Rights Reserved.

Licensed under the Apache License, Version 2.0 (the "License"). You may not use this file except in compliance with the License. A copy of the License is located at

    http://aws.amazon.com/apache2.0/

or in the "license" file accompanying this file. This file is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
