# Setup the zoo on a minikube environment

## building docker images 
 Either use minikube’s own Docker daemon to build the image, by pointing your local docker client to it with `eval $(minikube docker-env)` .
 Or read: https://blog.hasura.io/sharing-a-local-registry-for-minikube-37c7240d0615.

## Some tool sugestions
### windows
- install chocolatey https://chocolatey.org/install
- $ choco install minikube -y
