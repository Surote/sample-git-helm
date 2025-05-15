# sample-git-helm

This repository is configured as a Helm chart repository.
## Usage 
- `helm repo add swongpai-helm  https://surote.github.io/sample-git-helm`

- `helm search repo swongpai-helm` output as following
```
NAME                 	CHART VERSION	APP VERSION	DESCRIPTION
swongpai-helm/py-echo	0.1.0        	1.16.0     	A Helm chart for Kubernetes
```

- `helm install <NAME> swongpai-helm/py-echo <value.yaml>`