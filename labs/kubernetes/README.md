# Kubernetes

Estudos e experimentos com K8s — do básico ao avançado.

## Tópicos

- [ ] Arquitetura: control plane, nodes, etcd
- [ ] Pods, Deployments, ReplicaSets
- [ ] Services, Ingress, NetworkPolicy
- [ ] ConfigMaps e Secrets
- [ ] Persistent Volumes
- [ ] RBAC e segurança
- [ ] Helm charts
- [ ] Horizontal Pod Autoscaler
- [ ] Observabilidade: Prometheus + Grafana

## Ambiente local

Usar [kind](https://kind.sigs.k8s.io/) ou [minikube](https://minikube.sigs.k8s.io/) para clusters locais.

## Estrutura

```
kubernetes/
├── manifests/       # YAMLs de exemplo
├── helm/            # Charts customizados
└── scenarios/       # Cenários práticos end-to-end
```
