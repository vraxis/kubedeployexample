This project will house an example of running a nodejs server in conjunction with a static website which calls it and a redis instance.

Skaffold will be used in order to manage, at first, local development, with a goal of eventually using the same config to spin up environments with kubernetes in aws


In progress:
- Create dockerfiles for a helloworld nodejs app. Test with just docker TODO
- Install minikube and deploy nodejs server locally with skaffold TODO
- Add redis dockerfile in separate folder from node. confirm, deploys to k8 TODO
- Have node talk to redis instance TODO
- Add a static front end react project to the mix which calls nodejs TODO
- Deploy somewhere other than local TODO
- Have a hybrid environment with some code local, some services remote?



Windows:
https://medium.com/@JockDaRock/minikube-on-windows-10-with-hyper-v-6ef0f4dc158c hyperv needs a virtual switch configured. install kubectl, then minikube, configure hyperv
