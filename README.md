# K8s-Assignment
Run Applications Using a Deployment in Kubernetes
Create a Kubernetes cluster and ensure the kubectl CLI tool is configured to communicate with the cluster. Cluster must have two nodes that are not control plane hosts. Clusters can be created using minikubeLinks to an external site., KillercodaLinks to an external site., or Play with Kubernetes LabsLinks to an external site. (note: if using minikube ensure metrics-server service is running.
Create a deployment using the following .yaml file:
https://k8s.io/examples/application/deployment.yamlLinks to an external site. 

Display the information regarding the deployment and list the pods created by the deployment (take a screenshot and insert here).
Update the deployment using the following .yaml file:
https://raw.githubusercontent.com/kubernetes/website/main/content/en/examples/application/deployment-update.yamlLinks to an external site. 

Watch the deployment create the new pods and document the changes (take a screenshot and insert here).
Apply scaling to the nginx application by increasing the read replica count. Update the deployment using the following file:
https://raw.githubusercontent.com/kubernetes/website/main/content/en/examples/application/deployment-scale.yamlLinks to an external site. 

Verify and document the new pods in the deployment are created. Delete the deployment after documenting the new pods(take a screenshot and insert here).
