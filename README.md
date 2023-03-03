# misskey-docker-image
This is an automated unofficial daily build of misskey, based on the master branch.

You can find the latest fresh build from [here](https://github.com/mtripg6666tdr/misskey-docker-image/pkgs/container/misskey) and pull an image like:
```sh
docker pull ghcr.io/mtripg6666tdr/misskey:latest
```

To start instance of misskey, you should basically follow [the official instruction to create a misskey instance](https://misskey-hub.net/docs/install/docker.html).

Create your own `docker-compose.yml` from [`docker-compose.yml.example`](https://github.com/misskey-dev/misskey/blob/master/docker-compose.yml.example).  
You'll have to create config files like `.config/docker.env` and `.config/default.yml` and mount them to the docker container.  
Now it should work then.

## Copyright
The build script was originally written by [minetaro12](https://github.com/minetaro12) and distributed under MIT License.  
Thank you for the original author, minetaro12, and all contributors.
