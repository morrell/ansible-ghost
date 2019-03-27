# Morrell Ansible Playbook - Ghost

This playbook is designed to setup a ghost blog with docker and nginx.

Set the following variables to configure the site address and email for registering ssl certificates with certbot

```
vars:
    site_url: "<<INPUT SITEURL>>"
    cb_email: "<<CERTBOT EMAIL>>"
```
