# Mini projet de fin de formation Kubernetes - déploiement Odoo

### Pré-requis :
* Un cluster Kubernetes
* Longhorn installé sur le cluster

Pour déployer l'application :

`kubectl apply -k ./`

La page web d'admin d'Odoo est accessible à l'adresse IP du master node, sur le port 32000