AOSPA for Samsung Galaxy A71
------------------------------------

Create directories
```bash
mkdir aospa
cd aospa
```

Init the base manifest

```bash
repo init -u https://github.com/AOSPA/manifest -b uvite --depth=1
cd .repo 
git clone https://github.com/aospa-a71/local_manifests
cd ..
```

Then sync up with this command:
```bash
repo sync --current-branch --no-tags -j4
```
-------------
 
_Building from source_
---------------
```bash
./rom-build.sh a71
```
