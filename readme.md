# PetClinic Docker Build Pod Template Example for GKE On-Prem Hybrid

This is an example of running an existing Jenkins 2 master on a VM with a GKE On-Prem cluster using the [Kubernetes plugin](https://github.com/jenkinsci/kubernetes-plugin). This allows running an agent pod template on the cluster to handle pipeline tasks. See the [podTemplate folder](https://github.com/jefferyfry/spring-petclinic-docker-build-podTemplate-gkeonprem/tree/master/podTemplate) and the [Jenkinsfile](https://github.com/jefferyfry/spring-petclinic-docker-build-podTemplate-gkeonprem/blob/master/Jenkinsfile) for details. This pipeline runs a maven build, docker build, pushes the image to docker hub and then deploys the petclinic application to a GKE cloud cluster. This demonstrates a hybrid cloud use case and the scenario of deploying to a cloud staging cluster.

![gke-on prem hybrid - jenkins 2 on-prem](https://user-images.githubusercontent.com/6440106/52495340-3cab1300-2b85-11e9-921a-60b935eb50d4.png)



