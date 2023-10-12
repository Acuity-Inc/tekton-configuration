# tekton-configuration
YAML configurations for a CI/CD pipeline in Tekton

### Secret Creation
```
kubectl create secret docker-registry regcred \
--docker-server=https://index.docker.io/v1/ \
--docker-username=<username> \
--docker-password=<password> \
--docker-email=<user@email.com>
```
