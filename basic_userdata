#!/bin/bash
yum update -y 
yum install telnet nc net-tools -y 
yum install -y https://s3.amazonaws.com/ec2-downloads-windows/SSMAgent/latest/linux_amd64/amazon-ssm-agent.rpm
systemctl start amazon-ssm-agent
systemctl status amazon-ssm-agent

