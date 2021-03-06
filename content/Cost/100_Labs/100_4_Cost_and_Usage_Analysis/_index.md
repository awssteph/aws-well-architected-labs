---
title: "Level 100: Cost and Usage Analysis"
#menutitle: "Lab #3"
date: 2020-04-24T11:16:08-04:00
chapter: false
weight: 4
---
## Last Updated
June 2021

## Authors
- Nathan Besh, Cost Lead Well-Architected
- Matt Berk, Sr. Technical Account Manager

## Feedback
If you wish to provide feedback on this lab, there is an error, or you want to make a suggestion, please email: costoptimization@amazon.com

## Introduction
 This hands-on lab will guide you through the steps to perform analysis of your AWS cost and usage. The skills you learn will help you monitor your cost and usage, in alignment with the AWS Well-Architected Framework.

![Images/AWSBillReadme.png](/Cost/100_4_Cost_and_Usage_Analysis/Images/AWSBillReadme.png?classes=lab_picture_small)

## Goals
- Perform basic analysis of your cost and usage

## Prerequisites
- [AWS Account Setup]({{< ref "/Cost/100_Labs/100_1_AWS_Account_Setup" >}}) has been completed
- An AWS account with usage for more than 1 month


## Permissions required
- Log in as the Cost Optimization team, created in [AWS Account Setup]({{< ref "100_1_AWS_Account_Setup" >}})
- NOTE: There may be permission error messages during the lab, as the console may require additional privileges. These errors will not impact the lab, and we follow security best practices by implementing the minimum set of privileges required.

## Costs
- S3: Storage for enabling your Monthly Report in the Detailed Billing Reports, refer to S3 pricing https://aws.amazon.com/s3/pricing/

## Time to complete
- The lab should take approximately 10 minutes to complete

## Steps:
{{% children  /%}}

{{< prev_next_button link_next_url="./1_view_invoice/" button_next_text="Start Lab" first_step="true" />}}