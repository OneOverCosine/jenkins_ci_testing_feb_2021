# CI/CD with Jenkins

## What is CI/CD?
It stands for *continuous integration* and *continuous delivery and deployment*

### Continuous Integration
This is the first step in CI/CD.  
- Developers push code to a repository often
- A testing server checks the code automatically as it's pushed
- Developer gets feedback about the checks that have passed/failed

**CI benefits**  
- Bugs are found earlier, so they're fixed earlier
- Faster delivery than with manual testing
- Deploy more often (as code is ready quicker)

### Continuous Delivery (and Deployment)
Continuous delivery allows software to be released reliably whenever it's needed. This process need to be quick enough to happen often, which is why it's automated (for the most part).  
The deployment server determines what to do next based on the output it gets from the build server.  

**Continuous Delivery**
- Frequent deployment using automation
- May involve a manual step to approve a deployment
- The deployment itself is still automated

**Continous Deployment**  
- Fully automated. Every code change is deployed all the way to production
- No manual intervention/approvals

## CI/CD Tools
Here are some common tools avaible for a CI/CD pipeline

### Code
- AWS CodeCommit
- GitHub

### Build & Test
- AWS CodeBuild
- Jenkins CI

### Deploy & Provision
- AWS Elastic Beanstalk
- AWS CodeDeploy (Deploy)
- CloudFormation