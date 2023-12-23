install:
	helm dependency update ./jaeger-helm-chart
	helm install jaeger ./jaeger-helm-chart -f jaeger-helm-chart/values.yaml -n jaeger --create-namespace
uninstall:
	helm uninstall jaeger -n jaeger
template:
	helm template jaeger ./jaeger-helm-chart
dependencies:
	helm dependency update ./jaeger-helm-chart
