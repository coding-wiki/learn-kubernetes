# learn-kubernetes

## Introduction Videos

- [How Kubernetes works | Microsoft Azure](https://www.youtube.com/watch?v=daVUONZqn88)

## Getting Started

### Installing `kube-ctl`

```sh
brew install kubernetes-cli
kubectl version # To test it works
```

### Developing Locally

Install `hyperkit` (virtualisation lib)

```sh
brew install hyperkit
```

Install `minikube`:

```sh
brew cask install minikube
minikube config set vm-driver hyperkit
```

Create a `minikube` cluster with:

```sh
minikube start
```

Debugging:

If `minikube start` returns `machine does not exist`, run `minikube delete`

