# minio-mc-nsg

MinIO MC is a Object Storage client that implements the AWS S3 API.
There is currently no packages published of "mc", so I made this package.

There are a few limitations due snapd's sandbox:

* You can only upload/download files from your home directory.
* You can't read from hidden files (starting with a dot)
* On Ubuntu Core you need to manually connect the home interface

## Install

```
snap install minio-mc-nsg
```

If you like to use the shorter command "mc" add an alias:

```
sudo snap alias minio-mc-nsg mc
```
