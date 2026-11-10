# Hi, I'm Stuart Hernandez

I'm working toward a DevOps engineering role by building and operating
projects in my home lab. I'm focused on understanding how infrastructure
works, automating repeatable tasks, and documenting what I learn.

## What I've built

### Terraform + LocalStack infrastructure lab

Built an AWS-style infrastructure lab using Terraform and LocalStack
running in Docker on a separate Ubuntu server.

- Created a VPC and three subnets using calculated CIDR ranges.
- Defined a DynamoDB table and an IAM user with a read-only policy.
- Verified the deployed resources using CLI commands.
- Documented setup, deployment, verification, and teardown.
- Recorded lessons learned about subnetting and Terraform configuration.

The repository is currently private. I'm preparing it for public sharing.

## What I'm building next

Planning a Kubernetes platform using my spare computer and Raspberry Pis.

The project will grow in stages:

1. Configure machines and install RKE2 with Ansible.
2. Deploy an application using Helm.
3. Automate testing and image builds with GitHub Actions.
4. Manage deployments through Argo CD.
5. Add monitoring, backups, and recovery exercises.

I also plan to deploy AdGuard Home as a useful service on my home network.

## Tools I'm working with

Terraform · LocalStack · Linux · Docker · Git · GitHub

Next areas of focus: Ansible, Kubernetes, Helm, and GitOps.
