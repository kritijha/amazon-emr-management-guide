# Supported Instance Types<a name="emr-supported-instance-types"></a>

The following table describes the instance types that Amazon EMR supports\. For more information, see [Amazon EC2 Instances](https://aws.amazon.com/ec2/instance-types/) and [Amazon Linux AMI Instance Type Matrix](https://aws.amazon.com/amazon-linux-ami/instance-type-matrix/)\.

Not all instance types are available in all regions\. If you create a cluster using an instance type that is not available, your cluster may fail to provision or may be stuck provisioning\. For information about instance availability, see the [Amazon EC2 Pricing Page](https://aws.amazon.com//ec2/pricing), click the link for your instance purchasing option, and filter by **Region** to see if the instance type you select from the list below is available in the region\.

Beginning with Amazon EMR release version 5\.13\.0, all instances use HVM virtualization and EBS\-backed storage for root volumes\. When using Amazon EMR release versions earlier than 5\.13\.0, some previous generation instances use PVM virtualization\. These are indicated in the table\. For more information, see [Linux AMI Virtualization Types](http://docs.aws.amazon.com/AWSEC2/latest/UserGuide/virtualization_types.html)\.

Some instance types support enhanced networking\. For more information, see [Enhanced Networking on Linux](http://docs.aws.amazon.com/AWSEC2/latest/UserGuide/enhanced-networking.html)\.

Amazon EMR supports *Previous Generation Instances* to support applications that are optimized for these instances and have not yet been upgraded\. For more information about these instance types and upgrade paths, see [Previous Generation Instances](https://aws.amazon.com/ec2/previous-generation)\. 


| Instance Class | Instance Types | 
| --- | --- | 
| General purpose |  *m1\.medium\** \| *m1\.large\** \| *m1\.xlarge\** \| *m2\.xlarge\** \| *m2\.2xlarge\** \| *m2\.4xlarge\** \| *m3\.xlarge\** \| *m3\.2xlarge\** \| m4\.large \| m4\.xlarge \| m4\.2xlarge \| m4\.4xlarge \| m4\.10xlarge \| m4\.16xlarge \| m5\.xlarge \| m5\.2xlarge \| m5\.4xlarge \| m5\.12xlarge \| m5\.24xlarge  | 
| Compute optimized |  *c1\.medium\** \| *c1\.xlarge\** \| *c3\.xlarge\** \| *c3\.2xlarge\** \| *c3\.4xlarge\** \| *c3\.8xlarge\** \| c4\.large \| c4\.xlarge \| c4\.2xlarge \| c4\.4xlarge \| c4\.8xlarge \| c5\.xlarge \| c5\.2xlarge \| c5\.4xlarge \| c5\.9xlarge \| c5\.18xlarge \| *cc2\.8xlarge*  | 
| Memory optimized |  r3\.xlarge \| r3\.2xlarge \| r3\.4xlarge \| r3\.8xlarge \| r4\.xlarge \| r4\.2xlarge \| r4\.4xlarge \| r4\.8xlarge \| r4\.16xlarge \| *cr1\.8xlarge*  | 
| Storage optimized |  *hs1\.8xlarge\** \| *i2\.xlarge* \| *i2\.2xlarge* \| *i2\.4xlarge* \| *i2\.8xlarge* \| i3\.xlarge \| i3\.2xlarge \| i3\.4xlarge \| i3\.8xlarge \| i3\.16xlarge \| d2\.xlarge \| d2\.2xlarge \| d2\.4xlarge \| d2\.8xlarge  i3\-series instances available when using Amazon EMR version 5\.9\.0 and later\.   | 
| GPU instances |  *g2\.2xlarge* \| *cg1\.4xlarge* \| p2\.xlarge \| p2\.8xlarge \| p2\.16xlarge \| p3\.2xlarge \| p3\.8xlarge \| p3\.16xlarge  NVIDIA and CUDA drivers are installed on P2 and P3 instance types by default\.  | 

*\* Uses PVM virtualization AMI with Amazon EMR release versions earlier than 5\.13\.0\. For more information, see [Linux AMI Virtualization Types](http://docs.aws.amazon.com/AWSEC2/latest/UserGuide/virtualization_types.html)\.*