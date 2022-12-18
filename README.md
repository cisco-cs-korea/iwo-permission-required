# Required Permissions for Cisco Intersight Workload Optimizer

## What is Cisco Intersight Workload Optimizer?

Cisco Intersight Workload Optimizer is the premier solution for Application Resource Management (ARM) of cloud and virtual environments.

https://www.cisco.com/site/us/en/products/computing/hybrid-cloud-operations/intersight-workload-optimizer/index.html

<br>

## Required permissions for Amazone Web Service
|Permission Level|Required Permissions|Policy JSON|
|--|--|--|
|Read-Only (monitoring and recommendations)| ■ AmazonEC2ReadOnlyAccess<br>■ AmazonS3ReadOnlyAccess<br>■ AmazonRDSReadOnlyAccess<br>■ IAMReadOnlyAccess<br>■ AWSConfigRoleForOrganizations (only required for consolidated billing with the master account)| [iwo_aws_execute_actions_policy](./aws/iwo_aws_readonly_policy.json) |
|Execute Actions|■ AmazonEC2FullAccess<br>■ AmazonS3ReadOnlyAccess<br>■ AmazonRDSFullAccess<br>■ IAMReadOnlyAccess<br>■ AWSConfigRoleForOrganizations (only required for consolidated billing with the master account)| [iwo_aws_execute_actions_policy](./aws/iwo_aws_execute_actions_policy.json)

## Required permissions for Microsoft Azure
TBU

## Required permissions for VMware vsphere
TBU