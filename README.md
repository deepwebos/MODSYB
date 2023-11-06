
To initialize your local repository, use a 
command like this:

```bash
  repo init -u https://github.com/deepwebos/MODSYB.git -b 13.0
```
  
Then to sync up:
----------------

```bash
  repo sync -c --force-sync --no-tags --no-clone-bundle -j$(nproc --all) --optimized-fetch --prune
```

   . build/envsetup.sh
       lunch syberia_raphael-user
       mka syberia
