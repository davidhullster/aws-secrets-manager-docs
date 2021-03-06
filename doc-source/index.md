# AWS Secrets Manager User Guide

-----
*****Copyright &copy; 2020 Amazon Web Services, Inc. and/or its affiliates. All rights reserved.*****

-----
Amazon's trademarks and trade dress may not be used in 
     connection with any product or service that is not Amazon's, 
     in any manner that is likely to cause confusion among customers, 
     or in any manner that disparages or discredits Amazon. All other 
     trademarks not owned by Amazon are the property of their respective
     owners, who may or may not be affiliated with, connected to, or 
     sponsored by Amazon.

-----
## Contents
+ [What Is AWS Secrets Manager?](intro.md)
   + [Support and Feedback for AWS Secrets Manager](support-and-feedback.md)
+ [Getting Started with AWS Secrets Manager](getting-started.md)
   + [Key Terms and Concepts for AWS Secrets Manager](terms-concepts.md)
   + [AWS Secrets Manager Tutorials](tutorials.md)
      + [Tutorial: Storing and Retrieving a Secret](tutorials_basic.md)
      + [Tutorial: Rotating a Secret for an AWS Database](tutorials_db-rotate.md)
      + [Tutorial: Rotating a User Secret with a Master Secret](tutorials_db-rotate-master.md)
+ [AWS Secrets Manager Best Practices](best-practices.md)
+ [Authentication and Access Control for AWS Secrets Manager](auth-and-access.md)
   + [Overview of Managing Access Permissions to Your Secrets Manager Secrets](auth-and-access_overview.md)
   + [Using Identity-based Policies (IAM Policies) for Secrets Manager](auth-and-access_identity-based-policies.md)
   + [Using Resource-based Policies for Secrets Manager](auth-and-access_resource-based-policies.md)
   + [Determining Access to a Secret](auth-and-access_determining-access.md)
+ [Creating and Managing Secrets with AWS Secrets Manager](managing-secrets.md)
   + [Creating a Basic Secret](manage_create-basic-secret.md)
   + [Modifying a Secret](manage_update-secret.md)
   + [Retrieving the Secret Value](manage_retrieve-secret.md)
      + [Using the AWS-developed open source client-side caching components](use-client-side-caching.md)
   + [Deleting and Restoring a Secret](manage_delete-restore-secret.md)
   + [Managing a Resource-based Policy for a Secret](manage_secret-policy.md)
+ [Rotating Your AWS Secrets Manager Secrets](rotating-secrets.md)
   + [Permissions Required to Automatically Rotate Secrets](rotating-secrets-required-permissions.md)
   + [Configuring Your Network to Support Rotating Secrets](rotation-network-rqmts.md)
   + [Rotating Secrets for Supported Amazon RDS Databases](rotating-secrets-rds.md)
      + [Enabling Rotation for an Amazon RDS Database Secret](enable-rotation-rds.md)
      + [Customizing the Lambda Rotation Function Provided by Secrets Manager](rotating-secrets-customize-rds-lambda.md)
   + [Rotating Secrets for Amazon Redshift](rotating-secrets-redshift.md)
      + [Enabling Rotation for an Amazon Redshift Secret](enable-rotation-redshift.md)
   + [Rotating Secrets for Amazon DocumentDB](rotating-secrets-documentdb.md)
      + [Enabling Rotation for an Amazon DocumentDB Secret](enable-rotation-documentdb.md)
   + [Rotating AWS Secrets Manager Secrets for Other Databases or Services](rotating-secrets-other.md)
      + [Rotating AWS Secrets Manager Secrets for Other Databases or Services](rotating-secrets-create-generic-template.md)
      + [Enabling Rotation for a Secret for Another Database or Service](enable-rotation-other.md)
   + [Understanding and Customizing Your Lambda Rotation Function](rotating-secrets-lambda-function-customizing.md)
      + [Overview of the Lambda Rotation Function](rotating-secrets-lambda-function-overview.md)
      + [Rotating AWS Secrets Manager Secrets for One User with a Single Password](rotating-secrets-one-user-one-password.md)
      + [Rotating AWS Secrets Manager Secrets by Alternating Between Two Existing Users](rotating-secrets-two-users.md)
      + [Rotating AWS Secrets Manager Secrets For One User Supporting Multiple Credentials](rotating-secrets-one-user-multiple-passwords.md)
   + [Deleting Unused Lambda Rotation Functions](rotating-secrets-managing-functions.md)
+ [Using Secrets Manager with VPC Endpoints](vpc-endpoint-overview.md)
+ [Monitoring the Use of Your AWS Secrets Manager Secrets](monitoring.md)
+ [AWS Services Integrated with AWS Secrets Manager](integrating.md)
   + [Automating Secret Creation in AWS CloudFormation](integrating_cloudformation.md)
+ [Security in AWS Secrets Manager](security.md)
   + [Data Protection in AWS Secrets Manager](data-protection.md)
   + [Infrastructure Security in AWS Secrets Manager](infrastructure-security.md)
   + [Resiliency in AWS Secrets Manager](disaster-recovery-resiliency.md)
   + [Compliance Validation for AWS Secrets Manager](secretsmanager-compliance.md)
+ [AWS Secrets Manager Reference](reference.md)
   + [Quotas for AWS Secrets Manager](reference_limits.md)
   + [AWS Templates You Can Use to Create Lambda Rotation Functions](reference_available-rotation-templates.md)
   + [AWS Managed Policies Available for Use with AWS Secrets Manager](reference_available-policies.md)
   + [Actions, Resources, and Context Keys You Can Use in an IAM Policy or Secret Policy for AWS Secrets Manager](reference_iam-permissions.md)
+ [Troubleshooting AWS Secrets Manager](troubleshoot.md)
   + [Troubleshooting General Issues](troubleshoot_general.md)
   + [Troubleshooting AWS Secrets Manager Rotation of Secrets](troubleshoot_rotation.md)
+ [Calling the API by Sending HTTP Query Requests](query-requests.md)
+ [Document History for AWS Secrets Manager](document-history.md)
+ [AWS Glossary](glossary.md)