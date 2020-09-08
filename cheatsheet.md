# Cheatsheet

### Kubernetes

1) Test controllers

Deploy simple nginx app

```
kubectl apply -f apps/sample/pod.yaml
```

Destroy application

```
# chaos run 01-terminate-pod.yaml
```

Redeploy Pod

2) Add Steady-state-hypothesis

```
# chaos run 02-terminate-pod-ssh.yaml
```

Redeploy Pod

3) Add pause

```
# chaos run 03-terminate-pod-pause.yaml
```

Deploy controller

4) Test Pod status

```
# chaos run 04-terminate-pod-status.yaml
```

5) Testing the application

```
# chaos
```