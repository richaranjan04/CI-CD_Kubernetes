# CI-CD_Kubernetes

This Project has a CI/CD pipeline connected to azure. Whenever, new version of code is commited, the CI pipeline in azure automatically gets triggered and a docker image is created. The docker image is then pushed into kubernates service in the CD pipeline and we can see the changes in the hosted public IP.

Here is a Architecture for your reference.
![Arhitecture Diagram](https://github.com/harsh3105/CI-CD_Kubernetes/blob/master/Architecture.png)
