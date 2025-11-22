# 2048 App

## Create Fargate profile

```
eksctl create fargateprofile \
    --cluster demo-cluster \
    --region us-east-1 \
    --name alb-sample-app \
    --namespace game-2048
```

## Deploy the deployment, service and Ingress

```
kubectl apply -f https://raw.githubusercontent.com/kubernetes-sigs/aws-load-balancer-controller/v2.5.4/docs/examples/2048/2048_full.yaml
```

#Desired Output Image

![image alt](https://github.com/iam-Udaykiran/Uday/blob/729bd69a6f038abb045950efe9229ec1498e8772/2048game.png)


   
