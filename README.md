# app-ember-frontend-with-scp
This stack is useful if you want to allow people to develop on an ember frontend (with live reload) on a remote server.
This stack hosts an ember app and allows the code to be edited via an sftp connection.

You should provide an appriorate username and password for the sftp server as documented on https://github.com/atmoz/sftp . It may also be useful to properly chown the frontend directory (typically `chown -R 1000:0000 frontend`)
