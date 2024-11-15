You need to run these commands before running `mkosi`:
```bash
mkosi genkeys
systemd-id128 new > mkosi.machine-id
```

I also suggest creating `mkosi.rootpw` with the following content:
```bash
#!/usr/bin/env bash
echo 'root'
```