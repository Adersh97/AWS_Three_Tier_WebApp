# AWS_Three_Tier_WebApp

This image classification solution, deployed on AWS, boasts a resilient and highly available three-tier architecture 

1) Front End
2) Back End
3) Server


A Load Balancer intelligently distributes incoming requests to EC2 instances in the Back End, which dynamically scale to match demand. The system leverages SQS Messaging Queue for reliable inter-tier communication and robust handling of failed messages, with Lambda instantly activating instances to process new requests.
