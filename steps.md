Launch a Kubernetes cluster over AWS console using either eksctl or console. Please refer the below link for reference
https://docs.aws.amazon.com/eks/latest/userguide/create-cluster.html

Create the application pods usng deployment.yaml file by running the command kubectl apply -f deployment.yaml
Check the pods to be in running state using the command kubectl get pods -A
Launch the service of Load Balancer type to access the pods launched using the command kubectl apply -f service.yaml
Check the endpoint for the load balancer created kubectl get svc -A
Go over the browser to check the launched application and verify for the load balancer on AWs console