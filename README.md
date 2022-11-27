# Simple Vagrantfile, bringing up prometheus and grafana in docker containers
## Requirements:
- Hashicorp Vagrant;
- Ansible with <code>community.docker</code> plugins;
- Virtual Box as default VM provider for Vagrant;
## Installation
1. Create copy of this repo via <code>git clone</code>.
2. Fire up VM <code>vagrant up</code>.
3. Open browser and point it to <code>http://localhost:3000</code>.
4. Login with username <code>admin</code> and password <code>admin</code>.
5. Point to "Dashboards" menu on the left toolbar and select "Node exporter Full" dashboard. 
