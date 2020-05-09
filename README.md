# gcpdeploy
GCP Deployment Manager - Automation

Following task are completed as part of Google Cloud platform auotmation using deployment manager.
Following tasks are completed here.

- Configure the network
- Firewall configuration 
- Template cration for VM

This can be deployed directly using cloud shell.

#validate config being deployed
gcloud deployment-manager deployments create <name> --config=config.yaml --preview

#following command creates deployment
gcloud deployment-manager deployments update dminfra 
  
#additional commands which can help you in parametrization

1. gcloud deployment-manager types list | grep instance
2. gcloud deployment-manager types list | grep firewall
3. gcloud deployment-manager types list | grep network
