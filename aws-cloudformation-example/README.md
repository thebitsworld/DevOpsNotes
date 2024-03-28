This is an example to deploy services to AWS using cloudformation

01-infrastructure.yaml: 
Deploy common service as: VPC, DB, Cache, S3, Cloudfront and
the base infra EKS Fargate for futher service deploy

10-task-integration-service.yaml
Define EKS task and deploy integration service to EKS above

gitlab-ci-infra.yaml
An example gitlab-ci for CD infrastructure

gitlab-ci-service.yaml
An example gitlab-ci for CI/CD service