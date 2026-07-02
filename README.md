
```
git-ops
├─ README.md
├─ applications
│  ├─ idp.yaml
│  ├─ monitoring.yaml
│  └─ platform.yaml
├─ apps
│  ├─ idp
│  │  ├─ api
│  │  │  ├─ api-deployment.yaml
│  │  │  ├─ api-service.yaml
│  │  │  ├─ hpa.yaml
│  │  │  └─ kustomization.yaml
│  │  ├─ config
│  │  │  ├─ configmap.yaml
│  │  │  ├─ kustomization.yaml
│  │  │  └─ secret.yaml
│  │  ├─ ingress
│  │  │  ├─ ingres.yaml
│  │  │  └─ kustomization.yaml
│  │  ├─ kustomization.yaml
│  │  ├─ namespace.yaml
│  │  └─ worker
│  │     ├─ kustomization.yaml
│  │     └─ worker-deployment.yaml
│  └─ wss-app
│     ├─ deployment.yaml
│     └─ service.yaml
├─ bootstrap
│  └─ root.yaml
└─ platform
   ├─ argocd
   │  ├─ ingress.yaml
   │  └─ kustomization.yaml
   └─ monitoring
      ├─ grafana
      │  └─ grafana.yaml
      ├─ kustomization.yaml
      └─ prometheus
         └─ prometheus.yaml

```