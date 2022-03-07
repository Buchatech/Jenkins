# Jenkins on Kubernetes Deployment
Jenkins deployment for Kubernetes with persistent storage in the YAML folder.
  <br>
  <br>
 <b>NOTE:</b> This deploys a Load Balancer service on port 8080. To access Jenkins i.e. http://IPOFLB:8080
 <br>
 <br>
Get Jekins <b>initialadminpassword</b> from the logs after deployment:
<br>
kubectl get pods -n jenkins
<br>
kubectl logs <pod-name> -n jenkins
<br>
<br>
<img src="https://github.com/Buchatech/Jenkins/blob/main/initial-sign-in-Jenkins.png" alt="initial-sign-in-Jenkins"/>

