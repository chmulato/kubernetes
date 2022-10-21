"# Kubernetes Training" 

Installing the tools with Chocolatey:  <br /> 
01- choco install docker-engine   <br />
01- choco install docker-desktop   <br />
03- choco install k3d   <br />
04- choco install kubernetes-cli  <br />

Main command training:  <br />
01- k3d cluster create <br />
02- k3d cluster list  <br />
03- k3d cluster stop  <br />
04- k3d cluster delete  <br />
05- k3d cluster create --no-lb  <br />
06- kubectl get nodes  <br />
07- k3d cluster list  <br />
08- k3d cluster delete  <br />
09- k3d cluster create meucluster  <br />
10- kubectl get nodes  <br />
11- docker container ls  <br />
12- k3d cluster list  <br />
13- k3d cluster delete meucluster  <br />
14- k3d cluster create meucluster --servers 3 --agents 3  <br />
15- kubectl get nodes  <br />
16- docker container ls  <br />
17- k3d cluster list  <br />
18- k3d cluster delete meucluster  <br />
19- k3d cluster create <br />
