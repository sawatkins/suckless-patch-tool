# suckless-patch-tool
Shell script to automate adding, removing, and installing patches to [suckless](https://suckless.org/) software

---

### Installation
```
$ git clone https://github.com/sawatkins/suckless-patch-tool
$ cd suckless-patch-tool
$ chmod +x spt
```

### Usage
Apply patch:
`spt add patch_name /path/to/program/directory /path/to/patch`

Remove patch:
`spt rm patch_name /path/to/program/directory`
