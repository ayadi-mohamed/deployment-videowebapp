# jaeger-helm-chart
This is the Jaeger Helm chart.
# Usage
1- Create the secret that will be used to authenticate kibana to elastic search.
```yaml
apiVersion: v1
kind: Secret
metadata:
  name: jaeger-elastic-secret
type: Opaque
data:
    password: PIWPIW
```

2- Install the chart by running the following command:
```shell
make install
```