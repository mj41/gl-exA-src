This repository contains assets to programatically generate gl-exA git repository including the whole git history. gl-exA is an example repository for [gl-git-links](https://github.com/mj41/gl-git-links) tools.

Expected directory structure:

```
gl-exA/ - empty directory
gl-exA-scr/ - this repository
    assets/ - assets used to generate gl-exA repository
    rgen-conf.json - git-rgen configuration file
git-rgen - tool to generate git repositories programatically
```

Command to run:

```bash
cd git-rgen-tool
go run ./cmd/rgen --conf ../gl-exA-src/rgen-conf.json
```
