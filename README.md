# What this does?
This repo along with https://github.com/rahulgund/k8smanifest creates a Jenkins pipeline with GitOps to deploy code into a Kubernetes cluster. CI part is done via Jenkins and CD part is done via ArgoCD (GitOps).

# Jenkins is installed on EC2 instanace on AWS.
Required Jenkins Plugins are :- 
  Amazon EC2 plugin, 
  Docker plugin,
  Docker Pipeline,
  GitHub Integration Plugin,
  Parameterized trigger Plugin.
  
# ArgoCD is installed on Kubernetes cluster.
