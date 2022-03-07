# Jenkins on Kubernetes Deployment
Jenkins deployment for Kubernetes with persistent storage.
  <br>
  <br>
 NOTE: This deploys a Load Balancer service on port 8080. To access Jenkins i.e. http://IPOFLB:8080
 <br>
 <br>
Get Jekins initialadminpassword from the logs after deployment:
<br>
kubectl get pods -n jenkins
<br>
kubectl logs <pod-name> -n jenkins
<br>
<br>
https://github.com/Buchatech/Jenkins/blob/main/initial-sign-in-Jenkins.png****
