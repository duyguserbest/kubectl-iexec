# kubectl-iexec

This repository contains kubectl plugin to simplify interactive exec command.

Lists Kubernetes object to choose from to create kubectl exec -ti command.

![kubectl-iexec demo GIF](img/kubectl-iexec-demo.gif)

## Usage

```sh
kubectl iexec
```

## Installation

- Install fzf

```sh
git clone --depth 1 https://github.com/junegunn/fzf.git ~/.fzf
~/.fzf/install
```

- Install kubectl-iexec
Download the [`kubectl-iexec` file](https://raw.githubusercontent.com/duyguserbest/kubectl-iexec/master/kubectl-iexec) file and save as an executable to somewhere on $PATH 
