# Serverless Wordpress CDK Deployment

This CDK project utilizes Cloudfront, S3, ACM, and Route53 to deploy and serve a static website. In this case, the infrastructure is configured to deploy https://one11twenty.com.

## Architecture Diagram

![Sample deployment at one11twenty.com](https://imgur.com/PuzLXOA)

# Configuration

 * `npm run build`   compile typescript to js
 * `npm run watch`   watch for changes and compile
 * `npm run test`    perform the jest unit tests
 * `cdk deploy`      deploy this stack to your default AWS account/region
 * `cdk diff`        compare deployed stack with current state
 * `cdk synth`       emits the synthesized CloudFormation template
