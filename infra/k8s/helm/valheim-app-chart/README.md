## SETUP
## You'd need to specify context for helm before deploying
## export HELM_KUBECONTEXT=dev-dc1

## INSTALLATION

## ```helm install valheim-app-chart valheim-app-chart/ --namespace valheim-app -f valheim-app-chart/env/values.dev.yaml```


### Upgrade

## ```helm upgrade valheim-app-chart valheim-app-chart/ --namespace valheim-app -f valheim-app-chart/env/values.dev.yaml```


### Uninstall

##  ```helm uninstall valheim-app-chart valheim-app-chart/ --namespace valheim-app```
