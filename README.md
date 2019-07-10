# docker-helm

Containerized Helm client with some plugins to be used in CI/CD

Tools installed:
* helm
    * plugin diff
    * plugin secrets
* kubectl

Details about versionning:
* versionning of this docker image follow HELM version
* kubectl version to install can be passed as an argument of build. Default value is setted in Dockerfile.

*To get latest stable version of kubectl: https://storage.googleapis.com/kubernetes-release/release/stable.txt*

