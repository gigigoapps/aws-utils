# AWS-Utils

Utilities and resources to build and deploy Gigigo projects on Amazon Web Services.

## CloudFormation

* project-env-2az-vpc.template => Creation of network structure based on 2 availability zones for a new project environment
* project-env-3az-vpc.template => Creation of network structure based on 3 availability zones for a new project environment

### project-env-2az-vpc.template & project-env-3az-vpc.template

Enter `<Project>-<Env>-VPC` as stack name, where:

* `<Project>` matchs the `ProjectName` parameter value
* `<Env>` matchs the `Environment` parameter value
