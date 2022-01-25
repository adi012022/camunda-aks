# Camunda Spring Boot deployment on Azure Kubernetes Service (AKS)
This project illustrates how 
- a docker image based on a  [Camunda BPM Spring Boot](https://docs.camunda.org/get-started/spring-boot/) project is built,
- the [Azure CLI](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli) is used to create an Azure Container Reqgistry (ACR) and to push the image to it
- a Kubernetes Cluster on AKS is created using the Azure CLI
- an image is deployed on the Kubernetes cluster as a service and
- the service is exposed to the internet via a public IP using a [LoadBalancer](https://docs.microsoft.com/en-us/azure/aks/load-balancer-standard) or Ingress)
