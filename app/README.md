## Update deployment

```
k set image deployment k8s-web-hello k9s-web-hello=dore00mon/k8s-web-hello:2.0.0
```

## Check Rollout update status

```
❯ k rollout status deploy k8s-web-hello
```
