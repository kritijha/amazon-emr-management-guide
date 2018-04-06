# Automate Recurring Clusters with AWS Data Pipeline<a name="emr-manage-recurring"></a>

 AWS Data Pipeline is a service that automates the movement and transformation of data\. You can use it to schedule moving input data into Amazon S3 and to schedule launching clusters to process that data\. For example, consider the case where you have a web server recording traffic logs\. If you want to run a weekly cluster to analyze the traffic data, you can use AWS Data Pipeline to schedule those clusters\. AWS Data Pipeline is a data\-driven workflow, so that one task \(launching the cluster\) can be dependent on another task \(moving the input data to Amazon S3\)\. It also has robust retry functionality\. 

 For more information about AWS Data Pipeline, see the [AWS Data Pipeline Developer Guide](http://docs.aws.amazon.com/datapipeline/latest/DeveloperGuide/what-is-datapipeline.html), especially the tutorials regarding Amazon EMR: 

+  [Tutorial: Launch an Amazon EMR Job Flow](http://docs.aws.amazon.com/datapipeline/latest/DeveloperGuide/dp-launch-emr-jobflow.html) 

+  [Getting Started: Process Web Logs with AWS Data Pipeline, Amazon EMR, and Hive](http://docs.aws.amazon.com/datapipeline/latest/DeveloperGuide/dp-process-logs.html) 

+  [Tutorial: Amazon DynamoDB Import and Export Using AWS Data Pipeline](http://docs.aws.amazon.com/datapipeline/latest/DeveloperGuide/dp-importexport-ddb.html) 