What is Container:

Containers provide a standard way to package your application's code, configurations, and dependencies into a single object. Containers share an operating system installed on the server and run as resource-isolated processes, ensuring quick, reliable, and consistent deployments, regardless of environment.

docker login <git-lab-repo> -u <username> -p <passowrd>

docker build -t <tag_name> .
docker pus <tag_name>
docker tag <from_tag_name> <to_tag_name>
docker run -v <host_machine_DIRECTORY>:<docker_directpry> -it <tagName> /bin/bash


what is kubernetes: 
Orchestration for container
kubectl get --help
kubectl apply -f <deployment_file.yaml>
kubectl exec -it <podname> /bin/bash

kubectl get secret <secret_name> -o yaml
echo ehrgivbiueyt | base64 --decode
