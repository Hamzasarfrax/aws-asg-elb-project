# AWS Application Load Balancer + Auto Scaling Project

## Objective

Deploy highly available web servers using ALB and ASG.

## Services Used

- Amazon EC2
- Application Load Balancer
- Auto Scaling Group
- CloudWatch
- VPC

## Architecture

Users → ALB → EC2 Instances (Multi-AZ)

## Auto Scaling Policy

Target Tracking (CPU 50%)

## Testing

Used stress tool to simulate CPU spike.
Verified scaling in CloudWatch.
