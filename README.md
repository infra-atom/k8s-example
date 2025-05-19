# k8s-example
k8s-example yaml and helm

# FOR HELM 
cd nginx-app/
helm lint ~/nginx-app/
helm template  ~/nginx-app/
helm install ng-release ~/nginx-app/ --dry-run
helm install ng-release ~/nginx-app/ --dry-run --debug
helm install ng-release ~/nginx-app/
helm delete ng-release

# FOR YAML
cd example_yaml/
kubectl apply -f deploy.yaml
kubectl delete -f .
