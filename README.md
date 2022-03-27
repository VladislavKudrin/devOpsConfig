# How to provision the cluster to the Google Cloud

- Go to cluster-provisioning folder and run **terraform init**. It installs all dependencies.
- Run **terraform plan** to launch test for terraform
- Run **terraform apply** to provision cluster to the Google Cloud
- Repeat same steps for folders mongo-deployment-prod and mongo-deployment-test

This code will create cluster and namespaces for production and test environments