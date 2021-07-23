# k8s-jenkins
https://www.jenkins.io/doc/book/installing/kubernetes/


step 1:kubectl create -f jenkins.yaml --namespace jenkins

step 2:kubectl get pods -n jenkins

step 3:kubectl create -f jenkins-service.yaml --namespace jenkins

step 4:kubectl get services --namespace jenkins

step 5: kubectl get nodes -o wide
