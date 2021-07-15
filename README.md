# kubernetes_alura
https://worried-fridge-4fb.notion.site/Kubernetes-97bf780a67fc4b34b9ca790a5b1eb651

### Comandos: 
|O que faz?|Comando|
| -------- | -------- |
|Criação de pod|`kubectl run nginx-pod --image=nginx:latest`|
|Listar os pods|`kubectl get pods`|
|Acompanhar em tempo real|`kubectl get pods --watch`|
|Descrição do pod|`kubectl describe pod nginx`|
|Edição do pod|`kubectl edit pod nginx-pod`|
|Deletar pod|`kubectl delete pod nginx-pod`|
|Deletar pod a partir do arquivo|`kubectl delete -f .\primeiro-pod.yaml`|
|Executar dentro de um pod|`kubectl exec -it portal-de-noticias -- bash`|
|Listar os serviços|`kubectl get service` ou `kubectl get svc`|
