##Setting Up Minikube On Centos

####Requirements:
You need to have virtualbox installed before proceeding to running the following steps.

####Step 1

######Install Minikube

```
curl -Lo minikube https://storage.googleapis.com/minikube/releases/v0.25.0/minikube-linux-amd64
```

```
chmod +x minikube 
sudo mv minikube /usr/local/bin/
```

####Step 2.
######Install Kubectl

```
curl -Lo kubectl https://storage.googleapis.com/kubernetes-release/release/v1.9.0/bin/linux/amd64/kubectl 
```

```
sudo chmod +x kubectl 
sudo mv kubectl /usr/local/bin/
```

At this point kubernetes has been setup, so can run checks

####Step 3.
######Start minikube

```
minikube start 
```

######Confirm status

```
minikube status
```

You should see status that says "running"










