1. Create a namespace :
   kubectl create configmap nginx-configuration --namespace ingress-space

2. Create a config map
   kubectl create configmap nginx-configuration --namespace ingress-space

3. Create a ServiceAccount in the ingress-space namespace
   kubectl create serviceaccount ingress-serviceaccount --namespace ingress-space

4. Create roles and role binding

5. Create a deployment : ingress-controller.yaml

6. Create a service to make Ingress available to external users
   kubectl create -f service-ingress.yaml -n ingress-space

7. Create ingress
   kubectl create -f ingress-wear-watch -n app-space
