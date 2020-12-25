# Configure-Haproxy-using-Ansible
Using ansible configure Haproxy and update it's cofiguration file on each time managed node join inventory.

Haproxy.yml - This is the ansible playbook in this i have writtent the all tasks which helps us to configure Reverse Proxy Server(Haproxy)
as well as Apache web server(HTTPD). THis file run from the Ansible Controller Node.

haproxy.cfg - This is the file of configuration of haproxy. Ansible CN has contain copy of this file and written some extra code inside this using JINJA(It is the Ansible Framework that is provide extra power to ansible). I have been written a for loop that automaticlly get the all hosts(Perticular group) ips and append in haproxy.cfg that means bacend server ips automatically updated.


For any queries:
Contact me:

Email: umeshtyagi829@gmail.com

Linkedin: @umeshtyagi829
