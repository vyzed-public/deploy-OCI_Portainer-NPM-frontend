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

### Approach:
* As we proceed, we'll [track our progress on a per-issue basis](https://github.com/vyzed-public/deploy-OCI_Portainer-NPM-frontend/issues), in a "GSD using micro-tasks" manner.   
* Useful SOPs can be constructed from the [project history](https://github.com/vyzed-public/deploy-OCI_Portainer-NPM-frontend/issues?q=is%3Aissue%20sort%3Acreated-asc) (tracked via the ordered issues).
* A collection of useful [Resources, Tutorials, & Benchmark Projects](https://github.com/vyzed-public/deploy-OCI_Portainer-NPM-frontend/wiki/Useful-Resources,-Tutorials,-&-Benchmark-Projects) are in the project wiki.


### Results:

Deployments to the following active instances:  
* Reverse proxy service: https://proxy.vyzed.net
* Portainer GUI instance: https://ptner.vyzed.net



