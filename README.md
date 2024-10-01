# Implementar Lanchonete com K8s

## Criando PV e PVC

`kubectl apply -f pv.yaml`
`kubectl apply -f pvc.yaml`

## Banco de Dados

`kubectl apply -f mysql-srv.yaml`
`kubectl apply -f mysql-pod.yaml`

## App Lanchonete

`kubectl apply -f app-deployment`