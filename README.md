# generic-deploy

```bash
$ sudo apt update
$ sudo apt install nginx

$ sudo apt install python3-certbot-nginx
$ sudo certbot --nginx

$ sudo certbot renew --dry-run

$ chmod 660 /etc/systemd/service.service

$ sudo systemctl daemon-reload

$ sudo systemctl enable service.service

$ sudo systemctl start service.service
```