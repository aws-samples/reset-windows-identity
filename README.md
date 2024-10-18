## Reset Windows server identity settings using AWS Application Migration Service post-launch automation

Read the full blog post [Reset Windows server identity settings using AWS Application Migration Service post-launch automation](https://aws.amazon.com/blogs/migration-and-modernization/reset-windows-server-identity-settings-using-aws-application-migration-service-post-launch-automation) (Yet to be published)


### Isolated VPC
[PrivateVPCSSM.yml](./PrivateVPCSSM.yml) is a sample AWS CloudFormation template which creates a VPC, restricted Amazon EC2 Security Groups, Amazon EC2 Instance Profile and the required VPC endpoints to enable instances to communicate with AWS Systems Manager only.

### Automation Document
1. On the AWS Systems Manager console, choose **Documents** in the navigation pane.
1. Choose **Create document** *Command or Session*.
1. Enter a document name for example **Reset-Identity**.
1. Choose YAML as the document content.
1. Copy contents from [reset-identity.yml](./reset-identity.yml).
1. Choose **Create document**.


## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.

