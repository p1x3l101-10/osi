You need to run these commands before running `mkosi`:
```bash
mkosi genkey
systemd-id128 new > mkosi.machine-id
```

I also suggest creating `mkosi.rootpw`:
```
echo 'root' > mkosi.rootpw && chmod 600 mkosi.rootpw
```

Appearantly, you cannot build the image as a user, so make sure to run as root