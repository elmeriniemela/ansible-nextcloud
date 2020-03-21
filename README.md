## Ansible role installing private NextCloud server

After install, mount external SSD:

* `mount -t ext4 /dev/sda1 /opt/website/nextcloud/data/elmeri/files/T5-SSD`
* `sudo -u www-data php /opt/website/nextcloud/occ files:scan --all -vvv`
