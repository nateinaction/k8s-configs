1. Create secret
`kubectl create secret generic api-key --from_file=./api-key`
2. Create Deployment
`kubectl create -f ./deployment.yaml`
3. Create and expose Service
`kubectl create -f ./service.yaml`
