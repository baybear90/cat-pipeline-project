#   Cat Application Code Piipeline

In this demo series, we will be implementing a full code pipeline incorportating commit, build and deploy steps.

The advanced demo consists of 5 stages :-

- STAGE 1 : Configure Security & Create a CodeCommit Repo
- STAGE 2 : Configure CodeBuild to clone the repo, create a container image and store on ECR
- STAGE 3 : Configure a CodePipeline with commit and build steps to automate build on commit.
- STAGE 4 : Create an ECS Cluster, TG's , ALB and configure the code pipeline for deployment to ECS Fargate
- STAGE 5 : CLEANUP

![Architecture](https://github.com/acantril/learn-cantrill-io-labs/raw/master/aws-codepipeline-catpipeline/catpipeline-arch-all.png)

Services used: AWS IAM, CodeCommit, CodeBuild, CodePipeline, CodeDeploy, ECS/Fargate, ECR, S3, Docker, and ALB

## Architecture Diagrams

- [Stage1 - PNG](https://github.com/acantril/learn-cantrill-io-labs/raw/master/aws-codepipeline-catpipeline/02_LABINSTRUCTIONS/catpipeline-arch-stage1.png)
- [Stage1 - PDF](https://github.com/acantril/learn-cantrill-io-labs/raw/master/aws-codepipeline-catpipeline/02_LABINSTRUCTIONS/catpipeline-arch-stage1.pdf)
- [Stage2 - PNG](https://github.com/acantril/learn-cantrill-io-labs/raw/master/aws-codepipeline-catpipeline/02_LABINSTRUCTIONS/catpipeline-arch-stage2.png)
- [Stage2 - PDF](https://github.com/acantril/learn-cantrill-io-labs/raw/master/aws-codepipeline-catpipeline/02_LABINSTRUCTIONS/catpipeline-arch-stage2.pdf)
- [Stage3 - PNG](https://github.com/acantril/learn-cantrill-io-labs/raw/master/aws-codepipeline-catpipeline/02_LABINSTRUCTIONS/catpipeline-arch-stage3.png)
- [Stage3 - PDF](https://github.com/acantril/learn-cantrill-io-labs/raw/master/aws-codepipeline-catpipeline/02_LABINSTRUCTIONS/catpipeline-arch-stage3.pdf)
- [Stage4 - PNG](https://github.com/acantril/learn-cantrill-io-labs/raw/master/aws-codepipeline-catpipeline/02_LABINSTRUCTIONS/catpipeline-arch-stage4.png)
- [Stage4 - PDF](https://github.com/acantril/learn-cantrill-io-labs/raw/master/aws-codepipeline-catpipeline/02_LABINSTRUCTIONS/catpipeline-arch-stage4.pdf)

Adopted from Adrian Cantrill
AWS Expert
