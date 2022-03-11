# Jenkins on Kubernetes Deployment
<br>
<br>
Jenkins deployment for Kubernetes with persistent storage in the YAML folder.
  <br>
  <br>
 <b>NOTE:</b> This deploys a Load Balancer service on port 8080. i.e. http://IP:8080
 <br>
 <br>
Get Jekins <b>initialadminpassword</b> from the logs after deployment:
<br>
kubectl get pods -n jenkins
<br>
kubectl logs <pod-name> -n jenkins
<br>
<br>
<img src="https://github.com/Buchatech/JenkinsForK8swPersistentStorage/blob/main/images/initial-sign-in-Jenkins.png" alt="initial-sign-in-Jenkins"/>

