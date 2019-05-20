1. Create Postgres config maps resource
$ kubectl create -f postgres-configmap.yaml

2. Create storage related deployments
$ kubectl create -f postgres-storage.yaml

3. Create Postgres deployment
$ kubectl create -f postgres-deployment.yaml
