NPM-hosted copy-paste job of AWS cfn-response. AWS actively maintains the code that gets copy-pasted here--and periodically at that. If you're interested in actively developing this code--please fork and poke Amazon. If you notice the code here is out of sync with the latest version from Amazon, please send a pull request and link to where Amazon has posted the latest code.

Thanks, e'rybody!

#cfn-response module

This module contains functions that respond on behalf of custom resources you create using AWS CloudFormation.

The module includes a send method, which sends a response object to a custom resource by way of a ResponseURL, which is an Amazon S3 pre-signed URL.

Any Lambda function using this module stops running after executing the module's send method.

For more information, read the AWS documentation [here][1]

[1]: http://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-properties-lambda-function-code.html#cfn-lambda-function-code-cfnresponsemodule
