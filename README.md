# Simple Vagrantfile, bringing up prometheus and grafana in docker containers
## Requirements:
- Hashicorp Vagrant;
- Ansible;
- Virtual Box as default VM provider for Vagrant;
## Installation
Create copy of this repo via    
    git clone
Fire up VM
    vagrant up
Open browser and point it to 
    http://localhost:3000
Login with username <code>admin</code> and password <code>admin</code>.
Point to "dashboards" menu on the left toolbar and select "Node exporter Full" dashboard. 
