# Kubernetes Microservice Phonebook – Helm Repository

This repository hosts the packaged Helm chart for the Kubernetes Microservice Phonebook application.

## Chart Information

- Chart Name: phonebook
- Chart Version: 0.1.0
- Application Version: 1.0.0

## Add Helm Repository

```bash
helm repo add phonebook https://ramznagc.github.io/Kubernetes-Microservice-Phonebook-Helm/repository
helm repo update
```

## Search Chart

```bash
helm search repo phonebook
```

## Install Application

```bash
helm install my-phonebook phonebook/phonebook
```

## Verify Deployment

```bash
kubectl get pods
kubectl get services
```

## Uninstall

```bash
helm uninstall my-phonebook
```

This project is intended for educational purposes.