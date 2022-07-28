# Personal Server Backup
### A simple `.sh` to backup `www`, `logs`, `apache confs`, and `db dump` and `rsync` to local.
<br>

## What it does
It backups your server as multiple `tar` files and `rsync`s them to your local machine.

It backups the following:
- `/var/www/`
- `/var/log/`
- `/etc/apache2/`
- `mysqldump`

I run this twice a month (1,15) using `cron`. Here's the cron: `0 6 1,15 * *`.
