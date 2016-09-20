### syncthing-inotify on ubuntu
Use to enable active file sync with syncthing

Image version: 0.1-alpha

Note:  this is an expirimental image



*Example startup:*
```
docker run -ti --rm -v /shared-on-host:/path-in-container \
  --env "API_KEY=LOOKUP_THIS_KEY_IN_CLIENT"  \
  --env "TARGET=http://YOUR-RUNNING-SYNCTHING-CLIENT:8384" \
  --name syncthing-inotify jeroenbo/syncthing-inotify
```
