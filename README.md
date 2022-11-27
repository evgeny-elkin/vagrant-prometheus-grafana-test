# Simple Vagrantfile, bringing up prometheus and grafana in docker containers
## Requirements:
- Hashicorp Vagrant;
- Ansible;
- Virtual Box as default VM provider for Vagrant;
## Installation
1. Create copy of this repo via

    git clone

2. Fire up VM
    vagrant up
3. Open browser and point it to 
    http://localhost:3000
4. Login with username <code>admin</code> and password <code>admin</code>.
5. Point to "dashboards" menu on the left toolbar and select "Node exporter Full" dashboard. 
