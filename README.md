# selfhostedk8s
Collection self-hosted apps prepared for k8s deployment using kustomization templates.

## working enviroments and how I deploy things

* k3s cluster hosting some applications and exporters
* external VM keeping monitoring stack
* AD-hoc VM's 

All prepared apps are easy to deploy using argocd, flux or just applying kustomization template - just add namespace.

### exporters 
Prometheus exporters configured to work with external Prometheus instance 

##### [PVE exporter](https://github.com/prometheus-pve/prometheus-pve-exporter)

* Communicate with external PVE instace using API key and user
* Expose ingress for external prometheus scrape


## smallapps
Small but usefull apps for self-hosted lab enviroments