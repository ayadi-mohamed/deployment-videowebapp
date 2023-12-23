# elastic-helm-chart
This is elastic search helm chart.

# Usage
1- Add the Elastic search credentials secret:
```yaml
apiVersion: v1
kind: Secret
metadata:
  name: elastic-secret
data:
  ELASTIC_PASSWORD: PIWPIW
```

2- Install the chart by running the following command:
```shell
make install
```
