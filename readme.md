This repository contains assets to programmatically generate [gl-exA](https://github.com/mj41/gl-exA) git repository including the whole git history. gl-exA is an example and test repository for [gl-git-links](https://github.com/mj41/gl-git-links) tools. Tool used to generate the repository is [git-rgen-tool](https://github.com/mj41/git-rgen-tool).

Expected directory structure:

```
gl-exA/ - empty directory
gl-exA-src/ - this repository
    assets/ - assets used to generate gl-exA repository
    rgen-conf.json - git-rgen configuration file
git-rgen - tool to generate git repositories programatically
```

Command to (re)generate `gl-exA` repository:
```bash
cd git-rgen-tool
go run ./cmd/rgen --conf ../gl-exA-src/rgen-conf.json
```
