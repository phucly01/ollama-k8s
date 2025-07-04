# ollama-k8s
Running Kubernetes cluster with Open Webui and Ollama on local machine

#Folder Structure
- Main: Files to bring up kubernetes cluster
- metallb: Files to bring up load balancer for the kubernetes services
- ollama: Files to bring up open webui and ollam
- cert_manager: Manages cluster certificates
- ingress: Combines with metallb to provide single entry point for all services

#Recomended Installation Order
1. kubernetes-config
2. kubernetes-verify
3. cert_manager
4. metallb
5. ingress
6. ollama
