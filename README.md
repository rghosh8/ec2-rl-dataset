# ec2-rl-dataset

This repository contains datasets collected from 5 different EC2 instances. The resource configuration pair of (# of vCPUs, Memory Size in GB) acts as the action parameters for the RL. The transient CPU utilization (%) acts as state parameter. 



 | File Name  | EC2 Type    | # of vCPUs    | Memory Size (GB) |
| ----------- | ----------- | ------------- | -------------- |
| small.csv   | small t3a   |     2         | 2              |
| medium.csv  | medium t3a  |     2         | 4              |
| large.csv   | large t3a   |     2         | 8              |
| xlarge.csv  | xlarge t3a  |     4         | 16             |
| 2xlarge.csv | 2xlarge t3a |     8         | 32             |
