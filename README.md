# paperless_ftp_consumption
A docker "stack" with a single ftp-server which connects to a "consume"-Path of paperless-ngx

# env_variables:

> FTP_CONTAINER_NAME

The Name of the Docker-Container

> FTP_USERNAME

The Username of the FTP-User/FTP-Admin

> FTP_USERNAME

The Password, correspoinding to the FTP-User/FTP-Admin

> PAPERLESS_CONSUMPTION_DIR

The path to the consume-folder of paperless-ngx (see https://github.com/paperless-ngx/paperless-ngx/discussions/395)
