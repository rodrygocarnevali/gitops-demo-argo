# GitOps Demo com Argo CD

Este repositório contém os manifestos declarativos para deploy automatizado de uma aplicação Flask usando o Argo CD em um cluster Kubernetes.

## 📁 Estrutura

```
│   README.md
│
└───base
        argo.yaml
        deployment.yaml
        kustomization.yaml
        service.yaml
```

## 🚀 Como funciona

- O Argo CD monitora este repositório.
- A cada `commit` ou alteração no branch `main`, os recursos são sincronizados com o cluster Kubernetes.
- A aplicação Flask é implantada automaticamente no namespace `default`.

## 🧩 Requisitos

- Cluster Kubernetes com Argo CD instalado
- Acesso ao repositório público
- Permissão de sincronização via Argo CD

## 📝 Aplicação sincronizada

- Nome: `argocd-demo-api`
- Namespace: `argocd`
- Diretório: `base`
- Branch: `main`

## 📌 Licença

Este projeto é livre para uso educacional e profissional.

---