
```
yogesh.mangela@uk-lon01-mws54 compose_organisation_stack % ls

docker-compose.yml	rancher-compose.yml
yogesh.mangela@uk-lon01-mws54 compose_organisation_stack % kompose convert

WARN Unsupported root level volumes key - ignoring 
WARN Unsupported external_links key - ignoring    
WARN Volume mount on the host "/etc/vault" isn't supported - ignoring path on the host 

INFO Kubernetes file "secrets-deployment.yaml" created 
INFO Kubernetes file "secrets-claim0-persistentvolumeclaim.yaml" created 
INFO Kubernetes file "composeorganisationstack-token-persistentvolumeclaim.yaml" created 
INFO Kubernetes file "service-deployment.yaml" created 
INFO Kubernetes file "user-admin-deployment.yaml" created 
```
