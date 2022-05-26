Projeto do curso de Kubernets

Faça a instalação do k3d e do kubectl.

Instalar K3D:
•	https://k3d.io/

Instalar Kubectl:
•	https://kubernetes.io/docs/tasks/tools/

Na pasta ./k8s faça o seguinte:

Primeiro comando:
•	k3d cluster create meucluster --agents 3 --servers 3 -p "8080:30000@loadbalancer"

Segundo comando:
•	kubectl apply -f deployment.yaml

Para testar, acesse: http://localhost:8080
