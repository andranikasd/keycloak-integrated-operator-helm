# keycloak-operator

![Version: 1.21.0-SNAPSHOT](https://img.shields.io/badge/Version-1.21.0--SNAPSHOT-informational?style=flat-square) ![Type: application](https://img.shields.io/badge/Type-application-informational?style=flat-square) ![AppVersion: 1.21.0-SNAPSHOT](https://img.shields.io/badge/AppVersion-1.21.0--SNAPSHOT-informational?style=flat-square)

A Helm chart for EDP and official Keycloak Operators

**Homepage:** <https://github.com/andranikasd/keycloak-integrated-operator-helm>

## Maintainers

| Name | Email | Url |
| ---- | ------ | --- |
| Andranik Grigoryan | andranik.grigoryan.working@gmail.com | <https://github.com/andranikasd> |


## Source Code

* <https://github.com/andranikasd/keycloak-integrated-operator-helm>

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| keyclaokEdpOperator.affinity | object | `{}` |  |
| keyclaokEdpOperator.annotations | object | `{}` |  |
| keyclaokEdpOperator.clusterReconciliationEnabled | bool | `false` |  |
| keyclaokEdpOperator.extraVolumeMounts | list | `[]` |  |
| keyclaokEdpOperator.extraVolumes | list | `[]` |  |
| keyclaokEdpOperator.image.repository | string | `"docker.io/epamedp/keycloak-operator"` |  |
| keyclaokEdpOperator.image.tag | string | `"1.20.0"` |  |
| keyclaokEdpOperator.imagePullPolicy | string | `"IfNotPresent"` |  |
| keyclaokEdpOperator.name | string | `"keycloak-edp-operator"` |  |
| keyclaokEdpOperator.nodeSelector | object | `{}` |  |
| keyclaokEdpOperator.resources.limits.memory | string | `"192Mi"` |  |
| keyclaokEdpOperator.resources.requests.cpu | string | `"50m"` |  |
| keyclaokEdpOperator.resources.requests.memory | string | `"64Mi"` |  |
| keyclaokEdpOperator.tolerations | list | `[]` |  |
| keycloakInstanceOperator.image.pullPolicy | string | `"Always"` |  |
| keycloakInstanceOperator.image.repository | string | `"quay.io/keycloak/keycloak-operator"` |  |
| keycloakInstanceOperator.image.tag | string | `"24.0.2"` |  |
| keycloakInstanceOperator.name | string | `"keycloak-instance-operator"` |  |
| keycloakInstanceOperator.replicas | int | `1` |  |
| keycloakInstanceOperator.service.port | int | `80` |  |
| keycloakInstanceOperator.service.targetPort | int | `8080` |  |
| keycloakInstanceOperator.service.type | string | `"ClusterIP"` |  |
| keycloakInstanceOperator.serviceAccount.annotations | object | `{}` |  |
| keycloakInstanceOperator.serviceAccount.create | bool | `true` |  |

----------------------------------------------
