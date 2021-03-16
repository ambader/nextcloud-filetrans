# nextcloud-filetrans
direct upload files in ![nextcloud](https://github.com/nextcloud) and update record

send files via ssh
```console
scp -r /files/to/send root@127.0.0.1:.../nextcloud_data/user/files/target_folder
```

update user collection
```console
sudo -u www-data php /var/www/nextcloud/occ files:scan --all
```
