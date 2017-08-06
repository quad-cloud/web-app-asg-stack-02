# web-app-asg-stack-02
Stack Name: "web-app-asg-stack-02"
Create two AutoScale Groups (named: "web-asg-02" and "app-asg-02") in the Default VPC of "us-east-1" region
Properties for each ASG: Minimum Size: 1, Maximum Size: 3, Desired Size: 1
The instances in "app-asg-02" should only be accessible by instances in "web-asg-02"
