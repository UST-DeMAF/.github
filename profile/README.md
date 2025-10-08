# UST-DeMAF (University of Stuttgart - Deployment Model Abstraction Framework)

Various deployment automation technologies, such as Kubernetes and Terraform, are available to automate the deployment of applications. 
However, to use these technologies, developers must acquire specialized knowledge about these deployment technologies to create, maintain, and understand deployment models, for example, configuration files created with Kubernetes. 
The DeMAF is a tool that enables transforming such technology-specific deployment models into technology-agnostic deployment models that are modeled based on the Essential Deployment Metamodel (EDMM). 
The resulting technology-agnostic EDMM deployment models express deployments only by using the general modeling concepts that are supported by the 13 most prominent technologies. 
The resulting EDMM models can be understood without knowledge of the original deployment technology. 

The DeMAF transformation framework can be deployed with the Docker Compose scripts in the [Deployment Config Repository](https://github.com/UST-DeMAF/deployment-config)

The following publications have been developed in relation to the DeMAF:
* [Demo Paper](https://doi.org/10.1007/978-3-031-26886-1_19) at EDOC22 that demonstrates the first concept and implementation of the framework
