# FoundryVTT Management

Management for my Foundry VTT instance.

Pieces of Software involved:

- [ArgoCD](https://argoproj.github.io/cd/) for continuous delivery
- [Hashicorp Vault](https://www.hashicorp.com/products/vault) as secret store
- [External Secret Operator](https://external-secrets.io/latest/) to sync secret store with Kubernetes secrets
- [Argo Workflows](https://argoproj.github.io/workflows/) for backup jobs
- [Felddy FoundryVTT Container](https://github.com/felddy/foundryvtt-docker) as Foundry application container
- [Cert-Manager](https://cert-manager.io/) for automatic lets-encrypt certificates
- [Renovate](https://www.mend.io/renovate/) to update Foundry Docker Container and keep me informed about module updates
