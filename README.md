# Userify Cloudformation Example Templates

Example EC2/CloudFormation template(s) with examples demonstrating how you might deploy Userify SSH key management to your EC2 instances.

*   **[userify-ec2-instance.yaml](userify-ec2-instance.yaml)**

    This simple CloudFormation template will deploy a single instance running Amazon
    Linux in US-East-1 with the Userify shim connected to Userify Cloud, and can serve as a
    starting point for additional CloudFormation exploration. You can customize this template to
    load additional instance types and regions (using CloudFormation maps), point it at a local/
    self-hosted Userify instance or cluster, or add additional software to the instances and use
    this as the starting point for an AutoScaling Group Launch Configuration.
