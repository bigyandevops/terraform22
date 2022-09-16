Authentication and Configuration
Configuration for the AWS Provider can be derived from several sources, which are applied in the following order:

Parameters in the provider configuration

Environment variables

Shared credentials files

Shared configuration files

Container credentials

Instance profile credentials and region


provider "aws" {}

$ export AWS_ACCESS_KEY_ID="anaccesskey"

$ export AWS_SECRET_ACCESS_KEY="asecretkey"

$ export AWS_REGION="us-west-2"

$ terraform plan
