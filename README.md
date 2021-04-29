# command

To connect with ec2 server using linux
```sh
sudo ssh -i ~/Path/to/.pem  username@ipaddress
```

To remove all files from folder
```sh
sudo rm -r /folderPath
```

To copy files from local to server using linux
```sh
sudo scp -r -i ~/Path/to/.pem /Path/From/Local/* username@ipaddress:/path/to/server/folder
```
