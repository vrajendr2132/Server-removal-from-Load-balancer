# Server-removal-from-Load-balancer
Identify the high load/traffic serving proxy server and remove it from the load balancer servers
In an infra where the http traffic serving throgh proxy servers, to balance the traffic and load we can use load balancer servers. If the proxies have any bad performance which can cause high traffic/load serving through it may impact the http requests, so remove the impacted proxies from load balancer for better performance.


#Ansible playbook to remove proxy from load balancer

playbook file: proxyremover.yml
Inventory file: inventory.ini

#ansible-playbook proxyremover.yml -i inventory.ini -k -K
