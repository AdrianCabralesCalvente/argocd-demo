# hello-msg (Helm chart)
Despliega `hashicorp/http-echo` y devuelve un mensaje configurable.

## Valores principales
- `message`: texto a devolver
- `service.port`: puerto de escucha (por defecto 5678)

## Ejemplos
```bash
helm install demo . -n argocd-demo
helm upgrade demo . -n argocd-demo --set message="Nuevo mensaje"
