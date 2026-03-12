## Kubernetes Microservices Architecture

```mermaid
flowchart LR
A[User Request] --> B[Ingress]
B --> C[Service]
C --> D[Pod 1]
C --> E[Pod 2]
C --> F[Pod 3]
D --> G[Container]
E --> G
F --> G
```
