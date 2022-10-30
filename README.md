# Anotações Kubernetes

- kind create cluster
- kind get cluster <Lista todos os clusters>
- kind delete clusters kind
- kind create cluster --config=kind.yaml --name=fullcycle ## Criando o cluster
- kubectl config get-cluster <Lista todos os clusters que tenho>
- kubectl config use-context nome_do_contexto
- kubectl describe pods <Nome do Pod>
- kubectl get deployments Lista todos os deploys ativos
- kubectl rollout history <tipoObjecto: ex => Deployment > goserve
- kubectl rollout  undo <Volta para ultima versão>

- kubectl rollout  undo <Volta para ultima versão> <tipoObjecto: ex => Deployment > goserve --to-revision=<numero revision>
- kubectl port-forward <tipo do servico> portalocal:portakluster
- kubectl exec -it nome_pod -- <recurso que quer usar ex: bash>
- kubectl logs <nome pod>
## Service
 -  serve como um "api gateway" para direcionar a requisicao para um pod especifico# K8s
