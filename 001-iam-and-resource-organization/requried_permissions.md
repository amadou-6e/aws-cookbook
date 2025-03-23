# Required Permissions per Notebook Series

This file lists the **minimum AWS managed policies** required to follow along with each module in the AWS tutorial series. These policies can be attached to IAM users or groups in the AWS Console via the “Attach permissions policies” section.

The goal is to ensure you can run all examples in each notebook without running into permission errors, while still following best practices around scoped, managed access.

You are encouraged to assign only the policies necessary for the module you're working on. This avoids over-provisioning and helps you stay aligned with the principle of least privilege.

## Permissions by Tutorial Module

**001-aws-basics**:
- `IAMFullAccess`
- `ResourceGroupsandTagEditorFullAccess`

**002-networking**:
- `AmazonVPCFullAccess`
- `AmazonEC2FullAccess`

**003-compute-resources**:
- `AmazonEC2FullAccess`
- `AmazonSSMFullAccess`
- `AutoScalingFullAccess`
- `ElasticLoadBalancingFullAccess`

**004-serverless-compute**:
- `AWSLambda_FullAccess`
- `AmazonAPIGatewayAdministrator`
- `AWSStepFunctionsFullAccess`

**005-containers-and-kubernetes**:
- `AmazonECS_FullAccess`
- `AmazonEKSClusterPolicy`
- `AmazonEC2ContainerRegistryFullAccess`

**006-securing-access**:
- `IAMFullAccess`
- `SecretsManagerReadWrite`
- `AmazonSSMFullAccess`
- `AWSKeyManagementServicePowerUser`

**007-monitoring-and-costs**:
- `CloudWatchFullAccess`
- `AWSCloudTrail_FullAccess`
- `AWSBudgetsActionsWithAWSResourceControlAccess`
- `CostExplorerReadOnlyAccess`

**008-app-deployment**:
- `AWSElasticBeanstalkFullAccess`
- `AmazonS3FullAccess`
- `CloudFrontFullAccess`
- `AWSCodePipeline_FullAccess`
- `AWSCodeBuildAdminAccess`

**009-ai-and-ml-services**:
- `AmazonBedrockFullAccess`
- `ComprehendFullAccess`
- `AmazonTextractFullAccess`
- `AmazonRekognitionFullAccess`
- `AmazonS3FullAccess`

**010-opensearch-search**:
- `AmazonOpenSearchServiceFullAccess`
- `AWSLambda_FullAccess`
