keydb-cluster
=============
A KeyDB cluster chart for Kubernetes

Current chart version is `0.0.2`





## Chart Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| affinity | object | `{}` |  |
| fullnameOverride | string | `""` |  |
| image.keydb.pullPolicy | string | `"IfNotPresent"` |  |
| image.keydb.repository | string | `"eqalpha/keydb"` |  |
| image.keydb.tag | string | `"x86_64_v5.1.1"` |  |
| nameOverride | string | `""` |  |
| nodeSelector | object | `{}` |  |
| password | string | `""` |  |
| persistence.accessMode | string | `"ReadWriteOnce"` |  |
| persistence.enabled | bool | `true` |  |
| persistence.size | string | `"10Gi"` |  |
| replicaCount | int | `2` |  |
| resources | object | `{}` |  |
| service.autocluster | int | `8080` |  |
| service.keydb | int | `6379` |  |
| service.type | string | `"ClusterIP"` |  |
| tolerations | list | `[]` |  |
