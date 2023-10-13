# Terraform AWS EC2 Userdata Module

**This module is no longer being maintained** <br/>

This module is intended to help standardise user data components that repeat for a range of EC2 instances. Encapsulating commonly installed components in this module should reduce the complexity of having a consistent EC2 management componenets isntalled and correctly configured.

## UserData Options
All options are controlled by a feature flag, and are responsible for creating any required AWS resources.

### Session Manager
Session Manager provides shell access to a EC2 instance regardless of subnet location. Session Manager provides audited access and full session history. 

### AWS CloudWtach Agent
The cloudwatch Agent ships EC2 instance logs to a CloudWatch Log Stream to help with debugging EC2 instances
