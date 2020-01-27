# GCP-Simple-Deploymet-Manager
Automating the Deployment of Infrastructure Using Deployment Manager

![Image of Sample](assets/image.png?raw=true)

Using the 2 files in order to deploy with those simple commands:
```javascript
    mkdir dminfra
    cd dminfra/
    gcloud deployment-manager types list | grep network
    gcloud deployment-manager types list | grep firewall
    gcloud deployment-manager types list | grep instance
    gcloud deployment-manager deployments create dminfra --config=config.yaml --preview
    gcloud deployment-manager deployments update dminfra
```
