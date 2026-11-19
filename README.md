# AWS EC2 Instance Module

This module creates an AWS EC2 instance.

## Usage

module "ec2_instance" {
  source = "YOUR_TFC_ORG/ec2-instance/aws"

  ami_id        = "ami-12345678"
  instance_type = "t2.micro"
  instance_name = "demo-instance"
  environment   = "dev"
}
