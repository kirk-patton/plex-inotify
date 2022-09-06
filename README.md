# plex-inotify
Plex inotify systemd config

Reference: https://forums.plex.tv/t/plex-inotifier-auto-update-a-remote-plex-media-server-when-new-content-is-added-on-nas/141409

This is a simple systemd service 

In the main python file;

```daemonize = False```

/etc/systemd/system/multi-user.target.wants/plex-inotify.service



