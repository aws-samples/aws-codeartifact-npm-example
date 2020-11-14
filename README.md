# AWS CodeArtifact NPM Example

An example repository for creating, publishing, and installing npm packages
using [AWS CodeArtifact](https://aws.amazon.com/codeartifact/)

## Prerequisites

1. [Create an AWS account](https://aws.amazon.com/premiumsupport/knowledge-center/create-and-activate-aws-account/)
2. [Install and configure the AWS Command Line Interface](https://docs.aws.amazon.com/cli/latest/userguide/cli-configure-quickstart.html)
3. [Create a CodeArtifact repository](https://docs.aws.amazon.com/codeartifact/latest/ug/create-repo.html)

## Getting Started

### Find and replace the following

1. `my-repo` with your CodeArtifact repository name
2. `my-domain` with your CodeArtifact domain
3. `us-east-1` with the region of your CodeArtifact repository
4. `<ACCOUNT ID>` with your AWS account ID
5. `@myorg` with your org name

### Publish `my-package`

To publish `my-package`, change your working directory to [./my-package](./my-package)
and run `npm publish`

### Install from `my-app`

To install your new package, change your working directory to [./my-app](./my-app)
and run `npm install`

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.
