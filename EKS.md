# EKS

Comando para criar os cluster EKS.

Url base: https://docs.aws.amazon.com/eks/latest/userguide/getting-started-eksctl.html

`
eksctl create cluster \
--name test-malaca \
--version 1.14 \
--region us-east-1 \
--nodegroup-name standard-workers \
--node-type t3.medium \
--nodes 3 \
--nodes-min 1 \
--nodes-max 4 \
--ssh-access \
--ssh-public-key ~/.ssh/id_rsa.pub \
--managed
`

## Dashboard EKS

https://docs.aws.amazon.com/eks/latest/userguide/dashboard-tutorial.html

## Helm

https://docs.aws.amazon.com/eks/latest/userguide/helm.html


## Metricas

https://docs.aws.amazon.com/eks/latest/userguide/metrics-server.html


## Teste

https://docs.aws.amazon.com/eks/latest/userguide/keks-guestbook.html

## Helm  Nifi

helm install nifi cetic/nifi

link teste: http://a26429c066d7311ea9507023d3d2295d-174243365.us-east-1.elb.amazonaws.com/nifi/s