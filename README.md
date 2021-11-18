# Example for module aws_opsworks_stack
```
module "aws_opsworks_stack" {
  source="./modules/aws_opsworks_stack/"
    opsworks_name = "control-users-ssh-on-linux"
    opsworks_service_role_arn = "arn:aws:iam::123456789012:role/AWSOpsWorks_ServiceRole_for_ManageSSHKeys"
    opsworks_iam_instance_profile = "arn:aws:iam::123456789012:instance-profile/aws-opsworks-ec2-role"
    opsworks_color = "rgb(57, 131, 94)"
    opsworks_version = "12"
    opsworks_default_os = "Amazon Linux 2"
    opsworks_default_ssh_key_name = "aws-projeto-environment"
    opsworks_default_root_device_type = "ebs"
    opsworks_hostname_theme = "Layer_Dependent"
    opsworks_vpc_id = "vpc-1ab34567cdef89012"
    opsworks_default_subnet_id = "subnet-1234a5bc6de7890f1"
    opsworks_use_opsworks_sg = "true"
    opsworks_environment = "environment"
    opsworks_profile = "123456789012_ZupAdministratorAccess"
    opsworks_region = "us-east-1"
  }
```
