# Network Example Project
Create two services based upon the existing [frontend](https://github.com/hughbrien/frontend) service.  It's for testing multiple Kubernetes Deployments and Services and their respective configurations 
- catalog service
- shipping service
  
### Port Forward

helm install --kube-context=/Users/hughbrien/Software/k3s-context.yaml otterize otterize/otterize-kubernetes -n otterize-system --create-namespace 
