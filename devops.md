# DevOps

[roadmap](https://roadmap.sh/devops)

- Config management
  - Ansible
  - Puppet
  - Chef
  - Saltstac
  - cloud-init

- Provisioning
  - Puppet
  - Terraform
  - Salt
  - Ansible
  - Cloudformation

- Container Orchestration
  - K8s
  - Nomad
  - Rancher
  - Swarm
  - ECS

- CI/CD: 
  - Jenkins
  - Bamboo
  - GitLab CI/CD
  - CircleCI
  - Travis CI
  - Jfrog Pipelines
  - TeamCity

- Version Control: 
  - Git
  - SVN

- Monitoring & Alerting
  - Nagios
  - Zabbix
  - Prometheus
  - New Relic
  - Datadog

- Cloud Infrastructure
  - AWS
  - GCP
  - Azure
  - Digital Ocean

- Load Balancing
  - ALBs
  - HAProxy
  - Nginx

- Scripting/coding: 
  - Python
  - Bash
  - Groovy
  - Go


## CloudInit

> Before we get started with CloudInit, it is important to understand where CloudInit fits into the provisioning ecosystem. While it is possible to run CloudInit as a stand-alone provisioning system, it is far more common to use it in conjunction with another provisioning system, like Ansible, Chef, Puppet or Salt. In that case, you would simply use CloudInit to bring your new server to a state where the provisioning system can take over. Personally, I often use CloudInit in combination with Ansible.
> https://www.cloudsigma.com/an-introduction-to-server-provisioning-with-cloudinit/

[CloudInit, whitepaper](https://pages.ubuntu.com/rs/066-EOV-335/images/CloudInit_Whitepaper.pdf?utm_source=marketo&utm_medium=landingpage&utm_campaign=CY19_DC_Server_Whitepaper_CloudInit)

Most likely Kubernetes combined with CloudInit will be sufficient

## Planned Stack

- Infrastructure
  - Terraform
  - Digital Ocean resources(would like to add others later and run them alongside each other)
- Provisioning
  - CloudInit
  - Also another provisioner? Packer?
- Containers
  - Docker (containers themselves)
  - Kubernetes (orchestration)
