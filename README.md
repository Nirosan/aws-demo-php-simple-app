# aws-demo-php-simple-app
# Trigger deploy : 9
Application was created for use with an AWS Partner blog post and will be used for demonstration purposes for other web applications.

This web application utilizes the PHP scripting language to gather information system information and display that information using HTML/CSS/Chart.js.

Information gathered is a read-only file handler that reads information from /proc/. Information gathered is, CPU load, memory use, network packet types, and disk use. 

Features:
 - Simple PHP application tested on PHP 5.3 - 5.6
 - Load generation utility included

Other Items:
 - Currently no database test capabilities

Trying out new filter for tag
$ aws codepipeline put-webhook --cli-input-json file://webhook.json --region "ap-southeast-1"

{
    "jsonPath": "$.ref_type",
    "matchEquals": "tag"
}
