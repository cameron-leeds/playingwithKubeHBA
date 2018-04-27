# playingwithKubeHBA

Download the latest release with the command:

curl -LO https://storage.googleapis.com/kubernetes-release/release/$(curl -s https://storage.googleapis.com/kubernetes-release/release/stable.txt)/bin/linux/amd64/kubectl

 chmod +x ./kubectl
Move the binary in to your PATH.

 sudo mv ./kubectl /usr/local/bin/kubectl

Run kubectl version and met with 

The connection to the server localhost:8080 was refused - did you specify the right host or port?

 Download and install Minikube to run locally
 curl -Lo minikube https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64 && chmod +x minikube && sudo mv minikube /usr/local/bin/

