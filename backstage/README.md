1. Clone the repo. git clone https://github.com/keerthibingi/keycloak.git
2. cd backstage`
3. run the command `helm install bs . -f values.yaml -n backstage --timeout=10m`
4. Create env-vars secret by passing appropriate values in https://github.com/keerthibingi/keycloak/blob/main/backstage/bs-env-vars.yaml. Ex: `kubectl create secret generic backstage-env-vars --from-file bs-env-vars.yaml -n backstage`
5. 
