# Jenkins on Kubernetes Deployment
Jenkins deployment for Kubernetes with persistent storage.
  <br>
Get Jekins initialadminpassword from the logs after deployment:
<br>
kubectl get pods -n jenkins
<br>
kubectl logs <pod-name> -n jenkins
