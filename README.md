# alura-curso-kubernetes
Curso de Kubernetes da Alura


02
Pod e Deployment 

Nessa aula aprendemos que:

    para testar o kubernetes localmente usa-se o minikube
    para rodar o cluster usa-se minikube start
    para parar o cluster: minikube stop
    para limpar e apagar: minikube delete
    minikube usa alguma virtualização por baixo dos panos como virtualbox ou vmware
    para controlar o cluster usa-se kubectl
    o menor objeto de deploy é o Pod
    um Pod é o objeto que define como rodar o container (image, network, volumes, ports)
    um Pod sozinho não garante o estado desejado
    o comando kubectl create é usado para criar um Pod ou Deployment no cluster
    o Deployment se baseia no Pod e garante o estado desejado
    para receber infos sobre os Pods ou Deployments usamos kubectl get pods ou kubectl get deployments

