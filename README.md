You need to `mkosi genkeys` before running `mkosi`

I also suggest creating `mkosi.rootpw` with the following content:
```bash
#!/usr/bin/env bash
echo 'root'
```