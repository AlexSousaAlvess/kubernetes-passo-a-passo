# kubernetes-passo-a-passo
Material desenvolvido da live: Fullcycle - kubernetes passo a passo. Essa live é um preparatório para a semana Imersão fullcycle 13

Foi utilizado a ferramenta Kind pra instanciar um kluster
https://kind.sigs.k8s.io/

Comandos vistos na live:

- Lista todos os clusters:
kubectl get nodes

- Aplica o manifesto pod no kubernetes:
kubectl apply -f pod.yaml

- Aplica o manifesto replicaset no kubernetes:
kubectl apply -f replicaset.yaml

- Aplica o manifesto deployment no kubernetes:
kubectl apply -f deployment.yaml

- Aplica o manifesto service no kubernetes:
kubectl apply -f service.yaml

- Listar os clusters:
kubectl get node

- Listar os pods que estão instanciados:
kubectl get pods

- Listar os replicaset's que estão instanciados:
kubectl get rs

- Listar os deployment's que estão instanciados:
kubectl get deployment

- Listar os serviços que estão instanciados:
kubectl get svc

- Externaliza para o acessar:
kubectl port-forward svc/nginx-service 8080:80
