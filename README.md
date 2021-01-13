# suckless-patch-tool
Shell script to automate adding, removing, and installing patches to [suckless](https://suckless.org/) software.  Each patch is stored in its own clean branch and all branches are merged togeather before the program is built.

---

### Installation
```
$ git clone https://github.com/sawatkins/suckless-patch-tool
$ cd suckless-patch-tool
$ chmod +x spt
```

### Usage
Apply patch:
`spt add patch_name /path/to/program/git/repo /path/to/patch`

Remove patch:
`spt rm patch_name /path/to/program/git/repo`

After applying/removing a patch, the script will ask whether you want to build and install the updated program.  
