# Monitoring with AWS Cloud Watch


**Tasks:**

- Scalability with Autoscaling group and Highly availability with ALB Application Load Balancer
- Create an Autoscaling group - config min=1 max =3 - attach it to cloud watch
- Create a load balancer to balance the load in case of traffic increase or decrease
- Create Diagram for each step and Diagram for entire project/process
- Share you repos at 11:30 with initial progress - share the progress before lunch 1300 then at 1700

- = Second Iteration - SNS to send notification email/message 

## Autoscaling and Load Balancing

1. Select instance
    -  Actions, Instance settings, Attach to Auto Scaling Group

2. Create auto scaling group
    - Change group details
    - **Monitoring:***CloudWatch monitoring details:* Auto Scaling group metrics collect: Enable

3. Create a load balancer