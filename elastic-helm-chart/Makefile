install: dependencies
	helm install elastic ./elastic-helm-chart -f elastic-helm-chart/values.yaml -n databases --create-namespace
	kubectl apply -f secret.yaml
uninstall:
	helm uninstall elastic -n databases
template:
	helm template elastic ./elastic-helm-chart
dependencies:
	helm dependency update ./elastic-helm-chart
