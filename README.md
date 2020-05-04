# quickstart-stratus360-connect-with-service
## Stratus360 Amazon Connect Report Framework on AWS

This Quick Start deploys Stratus360 Amazon Connect Report Framework in the Amazon Web Services (AWS) Cloud. This Quick Start is for users who need a data logging and analysis solution for an Amazon Connect instance.

The Quick Start deploys AWS services to collect all logs produced by an Amazon Connect instance and places them in an Amazon Simple Storage Service (Amazon S3) bucket. Based on parameters selected during deployment, the logs are then sent to either Amazon Elasticsearch Service (Amazon ES) or Amazon QuickSight for analysis.

During deployment, you can choose to have CTR logs, ingested either by a Kinesis data stream into a Firehose delivery stream if other infrastructure requires a data stream, or by a Firehose delivery stream on DirectPut.
 
You can also choose to include an AWS Lambda function that reads Amazon Connect contact flow files from an S3 bucket and outputs a cleaned version with the location metadata changed. Note that this feature is in beta, so it might not work completely as intended. 

For more information and step-by-step deployment instructions, see [the guide](https://fwd.aws/Kee8j).

You can use the AWS CloudFormation templates included with the Quick Start to deploy Stratus360 Amazon Connect Report Framework in your AWS account in about 10 minutes.

This Quick Start provides the following options:

- Deploying Stratus360 Amazon Connect Report Framework for use with Amazon QuickSight
- Deploying Stratus360 Amazon Connect Report Framework with Amazon Elasticsearch Service

The following diagram shows Stratus360 Amazon Connect Report Framework for use with Amazon QuickSight.
![Quick Start architecture for Stratus360 Amazon Connect Report Framework](https://d1.awsstatic.com/partner-network/QuickStart/datasheets/stratus360-with-amazon-quicksight-architecture-diagram.2c3995e99b382213913df5c6d6143970ea6259d4.png)

For architectural details, best practices, step-by-step instructions, and customization options, see the [deployment guide](https://fwd.aws/KkYwn).

To post feedback, submit feature ideas, or report bugs, use the **Issues** section of this GitHub repo. If you'd like to submit code for this Quick Start, please review the [AWS Quick Start Contributor's Kit](https://aws-quickstart.github.io/).
