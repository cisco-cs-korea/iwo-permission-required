# IWO AWS IAM Policies

|Permission Level|Required Permissions|Policy JSON|
|--|--|--|
|Read-Only (monitoring and recommendations)| ■ AmazonEC2ReadOnlyAccess<br>■ AmazonS3ReadOnlyAccess<br>■ AmazonRDSReadOnlyAccess<br>■ AWSConfigRoleForOrganizations (only required for consolidated billing with the master account)| [iwo_aws_execute_actions_policy](iwo_aws_readonly_policy.json) |
|Execute Actions|■ AmazonEC2FullAccess<br>■ AmazonS3ReadOnlyAccess<br>■ AmazonRDSFullAccess<br>■ AWSConfigRoleForOrganizations (only required for consolidated billing with the master account)| [iwo_aws_execute_actions_policy](iwo_aws_execute_actions_policy.json)
