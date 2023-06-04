# Kubernetes

> ##Repositório curso Full Cycle 3.0 - Kubernetes

Kubernetes com kind


> Criando cluster
```
kind create cluster nome-do-cluster
```

> Vendos clusters
```
kind get clusters
```

> Vendos clusters com kubectl
```
kubectl config get-clusters
```

> Deletando cluster
```
kind delete clusters nome-do-cluster
```

> Criando cluster multi node
```
kind create cluster --config=k8s/kind.yaml --name=candido
```

> Usando o cluster
```
kubectl cluster-info --context kind-candido
```

> Saber quais clusters estão disponíveis e mudar o contexto
```
kubectl config get-clusters
```
```
kubectl config use-context nome-do-cluster
```

>
```

```

>
```

```