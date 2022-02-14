# ansible-aws-vpc
# Cloud automation with Ansible for AWS VPC

This is a step to step procedure for setting up AWS VPC(Virtual private cloud) with Ansible.

### In order to save your time you need:
- Configuration management of VPC
- Automatic setup(No human errors)
- Centralized change management
- Version control(IAAC)

### TOOLS
- Ansible(Ansible automation for configuration management of VPC).
- AWS (VPC setup with bastion host)

### FLOW OF EXECUTION
- Login to AWS
- Create EC2 instance to run ansible playbook
- Install Ansible
- Install boto
- Setup EC2 role for ansible
- Create a project directory
- Sample cloud task(with key pairs)
- Create variables file for VPC and bastion host
- Create VPC setup playbook
- Create bastion setup playbook
- Site.yml playbook to call both playbook at once
