# deploy-OCI_Portainer-NPM-frontend
Explore practical deployments onto the free service tier of Oracle Cloud Infrastructure of: 
* ...a simple Portainer instance offering a web GUI
* ...behind a reverse proxy (using Nginx Proxy Manager)
* ...on a front-end Docker network 

Using the following stack:
* Cloud IAAS: Free tier of OCI (Oracle Cloud Infrastructure)
  * OS: Ubuntu Minimal v24 
    * Docker (and Docker compose)
      * Portainer (for compose-based deployments via the Portainer Stack GUI) 
        * Reverse Proxy using NPM (NGINX Proxy Manager)

--- 

### Obnjective:

We want to set the stage for additional SaaS instance deployments, in the following project repo collection:
* [deploy-OCI_AdGuardHome_rp-NPM](https://github.com/vyzed-public/deploy-OCI_AdGuardHome_rp-NPM)
  * Explore practical deployments of simple AdGuard Home instance(s) onto the free service tier of Oracle Cloud Infrastructure via Portainer stacks using Docker composed container configs that implement a reverse proxy for front-end network services.
* [deploy-OCI_Ghost-MySQL_rp-NPM](https://github.com/vyzed-public/deploy-OCI_Ghost-MySQL_rp-NPM)
  * Explore practical deployments of a Ghost blog/CMS instance (using a MySQL data store) onto the free service tier of Oracle Cloud Infrastructure, behind a reverse proxy using Nginx Proxy Manager.
* [deploy-OCI_Nextcloud-MySQL_rp-NPM](https://github.com/vyzed-public/deploy-OCI_Nextcloud-MySQL_rp-NPM)
  * Explore practical deployments of a Nextcloud instance (using a MySQL data store) onto the free service tier of Oracle Cloud Infrastructure.
    
Each of these additional SaaS instance deployments will have their own unique requirements, issues, & challenges, but they all uniformly rely on an underlying Portainer instance and a reliable reverse proxy, and so can join our base set of service deployments in a dovetail manner.

---

### Approach:
* As we proceed, we'll [track our progress on a per-issue basis](https://github.com/vyzed-public/deploy-OCI_Portainer-NPM-frontend/issues), in a "GSD using micro-tasks" manner.   
* Useful SOPs can be constructed from the [project history](https://github.com/vyzed-public/deploy-OCI_Portainer-NPM-frontend/issues?q=is%3Aissue%20sort%3Acreated-asc) (tracked via the ordered issues).
* A collection of useful [Resources, Tutorials, & Benchmark Projects](https://github.com/vyzed-public/deploy-OCI_Portainer-NPM-frontend/wiki/Useful-Resources,-Tutorials,-&-Benchmark-Projects) are in the project wiki.

---

### Results:

Deployments to the following active instances:  
* Reverse proxy service: https://proxy.ns01.vyzed.net
* Portainer GUI instance: https://ptner.ns01.vyzed.net



