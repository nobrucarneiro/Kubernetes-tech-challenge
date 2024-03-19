Execução com Kubernetes
Entrar na pasta do Kubernetes

  cd k8s
Criar Persistent Volume

  kubectl apply -f pv-volume.yaml
Criar Persistent Volume Claim

  kubectl apply -f pv-claim.yaml
Criar Postgres Config Map

  kubectl apply -f postgres-config-map.yaml
Criar Postgres Service

  kubectl apply -f postgres-service.yaml
Criar Postgres Deployment

  kubectl apply -f postgres-deployment.yaml
Criar API Service

  kubectl apply -f api-service.yaml
Criar API Deployment

  kubectl apply -f api-deployment.yaml