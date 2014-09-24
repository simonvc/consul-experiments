Consul experiments

Launch servers with frankenstack.
Create ansible inventory.

Things that should go in a playbook..
* Install supervisord
* Push supervisord config with consul mentioned
* Create /etc/consul.conf and /etc/consul.d/ with the service defns
* Upload consul to /usr/bin/consul and the webui to /usr/share/consul/www
* Restart supervisord which will start consul
* JOIN all the nodes to one of the servers (or all to all or whatever)
* Replace the boxes /etc/resolv.conf with one that uses consul as a proxy



