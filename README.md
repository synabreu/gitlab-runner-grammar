# gitlab-runner-grammar

이 문서는 깃랩에 사용하던 간단한 문법을 오픈소스 예제와 깃랩을 사용하기 위한 여러가지 설치 방법, 환경 구성과 깃랩 명령어 문법 등을 정리해봤습니다. 따라서, 깃랩 명령어 문법은 [초급(Beginner)](https://github.com/synabreu/gitlab-runner-grammar/tree/main/Beginner/readme.md),[중급(Advanced)](https://github.com/synabreu/gitlab-runner-grammar/tree/main/Advanced/readme.md),[도커(Docker)](https://github.com/synabreu/gitlab-runner-grammar/tree/main/Docker/readme.md) 등을 사용할 수 있도록 서브 폴더로 나누어 놓았습니다. 

참고로 깃랩(GitLab) 이란 국내와 해외에서 잘 알려진 각종 애플리케이션 소프트웨어를 완전한 데브옵스(DevOps) 플랫폼으로 공동으로 계획, 구축, 보안 및 배포할 수 있는 기능을 포함한 플랫폼을 뜻합니다. 따라서,깃랩은 확장 가능하며 온프레미스 또는 클라우드 스토리지에서 호스팅할 수 있습니다. 또한 wiki, 문제 추적, IDE 및 CI/CD 파이프라인 기능이 포함되어 있어 쉽고 편리하게 사용할 수 있습니다. GitHub와 마찬가지로 정적 웹페이지를 호스팅하기 위한 무료 GitLab Pages 제품도 제공하며 버전 12.1 이후 HTTPS 지원을 위한 Let's Encrypt 옵션도 제공합니다.

### 설치방법

사용자 운영체제에 맞게 GitLab 과 GitLab Runner 를 설치할 수 있습니다. 초보자들에게는 깃랩 도커 이미지를 사용하기를 추천드립니다. 

1. [Install GitLab Docker images](https://docs.gitlab.com/ee/install/docker.html)
2. [Install Kubernetes](https://docs.gitlab.com/operator/)
3. [Install GitLab Runner on macOS](https://docs.gitlab.com/runner/install/osx.html)
4. [Install GitLab Runner on Windows](https://docs.gitlab.com/runner/install/windows.html)
5. [Run GitLab Runner in a container](https://docs.gitlab.com/runner/install/docker.html)
6. [GitLab Runner 로컬 (Mac, Windows) 설치 및 구성 가이드](https://insight.infograb.net/docs/cicd/local_runner_setting/#docker-compose%EB%A5%BC-%EC%82%AC%EC%9A%A9%ED%95%98%EC%97%AC-gitlab-runner-%EC%84%A4%EC%B9%98-%EB%B0%8F-%EC%8B%A4%ED%96%89)

로컬 환경에 설치하지 않고 클라우드 서비스 프로바이더(CSP)에 설치하는 방법은 다음과 같습니다.

1. [Install GitLab on AWS using the community AMIs provided by GitLab - AWS implementation patterns](https://docs.gitlab.com/ee/install/aws/?_gl=1*tks52v*_ga*MjM1MzMzMzguMTY2ODQ4ODczOA..*_ga_ENFH3X7M5Y*MTY3MDI5MDYxNS40Mi4xLjE2NzAyOTMwMjkuMC4wLjA.)
2. [Install amazon linux 2, CentOS 2, as official Linux Package](https://about.gitlab.com/install/#amazonlinux-2)
3. [Install GitLab on AWS using the community AMIs provided by GitLab](https://docs.gitlab.com/ee/install/google_cloud_platform/index.html)
4. [Install GitLab on Microsoft Azure](https://docs.gitlab.com/ee/install/azure/index.html)

### 문법자료

1. [Advanced configuration:](https://docs.gitlab.com/runner/configuration/advanced-configuration.html#the-runnersmachine-section)

### 참고자료

1. [Deploying Your App With ECS & Gitlab CI/CD](https://medium.com/swlh/deploying-your-app-with-ecs-gitlab-ci-cd-e211e6f103e1)
2. [Gentle Introduction to How AWS ECS Works with Example Tutorial](https://medium.com/boltops/gentle-introduction-to-how-aws-ecs-works-with-example-tutorial-cea3d27ce63d)
3. [Push your Docker containers from GitLab to Amazon ECR](https://devops.cisel.ch/push-your-docker-containers-from-gitlab-to-amazon-ecr)
4. [Implementing Alternate CI/CD Pipeline using AWS and GitLab](https://blog.searce.com/implementing-alternate-ci-cd-pipeline-using-aws-and-gitlab-874968515601)
5. [How to Configure your own GitLab Runner with a Docker Executor on AWS EC2](https://medium.com/devops-with-valentine/how-to-configure-your-own-gitlab-runner-with-a-docker-executor-on-aws-ec2-d76c7be0660d)
6. [Using Gitlab CI with AWS Container Registry](https://medium.com/@stijnbe/using-gitlab-ci-with-aws-container-registry-ecaf4a37d791)
7. [Configuring .gitlab-ci.yml with AWS EC2 for Continuous Integration (CI) or Continuous Deplyment (CD)](https://medium.com/hackernoon/configuring-gitlab-ci-yml-150a98e9765d)
8. [How to deploy with Gitlab-Ci to EC2 using AWS CodeDeploy/CodePipeline/S3](https://stackoverflow.com/questions/38671818/how-to-deploy-with-gitlab-ci-to-ec2-using-aws-codedeploy-codepipeline-s3/38672045#38672045)
9. [Event-driven architecture for using third-party Git repositories as source for AWS CodePipeline](https://aws.amazon.com/ko/blogs/devops/event-driven-architecture-for-using-third-party-git-repositories-as-source-for-aws-codepipeline/)
10. [Deploy and Manage Gitlab Runners on Amazon EC2](https://aws.amazon.com/ko/blogs/devops/deploy-and-manage-gitlab-runners-on-amazon-ec2/)
11. [How to run test on GitLab CI Locally](https://www.browserstack.com/guide/run-test-on-gitlab-ci-locally)
12. [Tutorial: Create and run your first GitLab CI/CD pipeline](https://docs.gitlab.com/ee/ci/quick_start/)
13. [Configure GitLab CI Runner with Docker executor using AWS EC2](https://www.youtube.com/watch?v=HGJWMTNeYqI)
14. [How to set up your SSH key for GitLab on macOS](https://medium.com/devops-with-valentine/2021-how-to-setup-your-ssh-key-for-gitlab-on-macos-dfccec6904fb)
15. [Push your Docker containers from GitLab to Amazon ECR](https://devops.cisel.ch/push-your-docker-containers-from-gitlab-to-amazon-ecr)
16. [Jenkins integration](https://docs.gitlab.com/ee/integration/jenkins.html)
17. [How to install Jenkins server on a AWS Linux Instance](https://medium.com/@kartheeksaip/how-to-install-jenkins-server-on-a-aws-linux-instance-53471c22dc73)
18. [Create a Jenkins Pipeline](https://about.gitlab.com/handbook/customer-success/demo-systems/tutorials/integrations/create-jenkins-pipeline/)
19. [Autoscaling GitLab CI on AWS Fargate](https://docs.gitlab.com/runner/configuration/runner_autoscale_aws_fargate/)
20. [Autoscaling GitLab Runner on AWS EC2](https://docs.gitlab.com/runner/configuration/runner_autoscale_aws/)
