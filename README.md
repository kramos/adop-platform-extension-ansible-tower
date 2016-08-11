# Ansible Tower Server Platform Extension
This platform extension spins up a blank Ansible Tower server with Ansible Tower installed making use of the AWS-type platform extension. 

Ansible Tower is a purely commerical product, so you will need a license to use the tower.  Trial licenses are available from Redhat.

## Getting Started

Follow the platform extension loading instructions below:
```
services/<the hosting provider where you want the platform extension to be loaded>/README.md
```

# Accessing your Ansible Tower server
The URL to access the Ansible Tower server will be in the following format:
``` https://EC2-Service-Extension-<extension-number>.<ADOP-public-IP>.xip.io/#/home ```

Once the platform extension has been loaded, the Ansible Tower server will be proxied by Nginx.

The default access credentials for the chef server web UI (once you have loaded the platform extension) are as follows:

 * username: admin
 * password: You will need to ssh to the server to find this...
 

