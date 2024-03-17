# Ansible: pterodactyl-panel

## TODO 

- Make roles idempotent

## Requirements

- Ubuntu 22.04 

## Variables

| Name | Default | Description |
| ---- | ------- | ----------- |
| pteropanel_hostname | "pterodactyl-panel.local" | Hostname used for the panel |
| pteropanel_mysql_password | "pterodactyl" | Password for the pterodactyl DB user |
| pteropanel_ssl | false | Do we want SSL/HTTPS? |
| pteropanel_letsencrypt | false | Do we want to request a certificate (also set pteropanel_ssl!) |
| pteropanel_le_email | "email@example.com" | The e-mail to use for the Let's encrypt certificate |
| pteropanel_user_mail | "email@example.com" | E-mail of the admin user
| pteropanel_user_password | "password" | Password of the admin user
| pteropanel_user_name | "admin" | Username of the admin user