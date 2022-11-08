## helm repo
```shell
# CICD
helm repo add gitlab https://charts.gitlab.io/
helm repo add harbor https://helm.goharbor.io
helm repo add jenkins https://charts.jenkins.io
helm repo add spinnaker https://helmcharts.opsmx.com/

# Others
helm repo add rancher-<CHART_REPO> https://releases.rancher.com/server-charts/<CHART_REPO>
helm repo add bitnami https://charts.bitnami.com/bitnami
helm repo update
```


## config
gitlab - hosts - domain / gitlab name,https
gitlab - ingress - enabled false
gitlab - cermanager - disable

jenkins - secrets

harbor - ingress - hosts (core)
harbor - externalURL

