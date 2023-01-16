# How to convert Docker Installation to Podman and Keep all the existing Config with Ansible Playbooks

* Backup Docker Config
  * SSL Certificates
  * Registry Authentification
  * Registry Config
  * Storage Config
* Backup existing containers config, images and data
  systemd files
  images
  application data
  
* Create and deploy Podman Config
* Recreate service md files for automatic container startup on new RHEL server
* Restore Application local data
