### alb-http-to-https-redirection.config
This configuration file usage resources to configure HTTP to HTTPS auto redirection at application load balancer (ALB) layer. This will not work with an environment using other load balancer (Classic/Network).

### autoscaling-cloudwatch-group-metrics.config
Configures your environment's Auto Scaling Group to send group metrics to Amazon CloudWatch at 1-minute intervals.

### autoscaling-memory-utilization-cwagent.config
This configuration file will create custom CloudWatch metrics and alarms to monitor memory usage of EC2 instances and trigger auto scaling events.  You can find more information about configuring the CloudWatch agent here: https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/customize-containers-cw.html#customize-containers-cw-update-roles

### autoscaling-memory-utlization-AL1.config  
*NOTE: This configuration file only applies to environments running on Amazon Linux AMI (preceding Amazon Linux 2).  For a configuration file that works with Amazon Linux 2 or later, see configuration file: [autoscaling-memory-utlization.config](autoscaling-memory-utlization.config).*
<br/>
This configuration file will create custom cloudwatch metrics along with alarms to monitor memory usage of EC2 instances and Trigger auto-scale events based on cloud watch alarms. You can find more information about custom monitoring script here: https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/customize-containers-cw.html#customize-containers-cw-update-roles.<br/>  

### autoscaling-terminate-newest-instance.config
Terminate newest instance in autoscaling group at the time of scale down event

### autoscaling-triggers-createnew.config
Add scaling triggers to your environment's AutoScaling group, in addition to those provisioned by Elastic Beanstalk.

### autoscaling-triggers-customize.config
Modify the scaling triggers that Elastic Beanstalk creates for your environment's Auto Scaling group.

### autoscaling-triggers-disabledefault.config
Disable the scaling triggers that Elastic Beanstalk creates for your environment's Auto Scaling group.

### loadbalancer-accesslogs-existingbucket.config
Configure the load balancer in your environment to upload access logs to an existing bucket that you have configured to allow ELB write access.

### loadbalancer-accesslogs-newbucket.config
Create a new bucket and configure the load balancer to write access logs to it.

### sns-topic.config
Create an SNS topic for notifications, or to use in your application.
