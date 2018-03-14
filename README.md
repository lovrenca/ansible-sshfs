# SSHFS
Ansible sshfs role mounts remote filesystems via SSHFS.

## Variables
* sshfs_mounts - list of object containing mount information - one mount will be created fore each containing object.
  * name: name of the moutn - for reference
  * src: url of the mount ~ `<user>@<host>:<path>`
  * path: mount point.

## Notes
The configured server must have the root user with ssh access to the remote which we're mounting.
