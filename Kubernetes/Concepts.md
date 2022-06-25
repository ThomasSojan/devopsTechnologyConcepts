# Kubernetes Concepts
## Components
### Pods
-> Smallest unit of K8s<br>
-> Abstration over container<br>
-> Usually one application per pod<br>
-> Each pod get its own IP address<br>
-> Pods are ephemeral<br>
-> New Ip address created on recreation<br>


### Service
-> Permanent IP address that can be attached to a pod<br>
-> lifecycle of service and pods are not connected<br>
-> **External Service** is a service that is open public<br>
-> **Internal Service** is a service that can't expose to public like database service<br>
-> **Ingress** is a component that give domain name to service<br>

### Configmaps and Secrets




