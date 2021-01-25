# Docker compose file for nginx in Windows

When creating a nginx docker image, you may encounter following error in windows.

> ERROR: for nginx_test_web_1  Cannot start service web: OCI runtime create failed: container_linux.go:370: starting container process caused: process_linux.go:459: container init caused: rootfs_linux.go:59: mounting "/conf/nginx.conf" to rootfs at "/var/lib/docker/overlay2/a753f7b016ca2d22a18821f6badddf1f44a6ee00185fd5fcd99411f6be403210/merged/etc/nginx/nginx.conf" caused: not a directory: unknown: Are you trying to mount a directory onto a file (or vice-versa)? Check if the specified host path exists and is the expected type
