# GCP-Simple-Deploymet-Manager-
Automating the Deployment of Infrastructure Using Deployment Manager

![Image of Sample](image.png?raw=true)

![Image of Sample](https://github.com/nnatbynet/GCP-Simple-Deploymet-Manager-/blob/master/image.png)

![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)

Using the 2 files in order to deploy with those simple commands:
    1  mkdir dminfra
    2  cd dminfra/
    3  gcloud deployment-manager types list | grep network
    4  gcloud deployment-manager types list | grep firewall
    5  gcloud deployment-manager types list | grep instance
    6  gcloud deployment-manager deployments create dminfra --config=config.yaml --preview
    7  gcloud deployment-manager deployments update dminfra
