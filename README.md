memoryleak.nfs-mounts
=====================

Create NFS mount entries using SystemD.

Requirements
------------

None

Role Variables
--------------

```
nfs_mounts:
  - nfs_server: truenas.localnetwork
    nfs_path: /mnt/data
    nfs_unit_name: mnt-data
    nfs_mount: /mnt/data

```

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: memoryleak.nfs-mounts }

License
-------

MIT

Author Information
------------------

Haydar Ciftci <haydar.ciftci@gmail.com>
