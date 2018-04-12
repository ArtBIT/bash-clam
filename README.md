# CLAM
[![GitHub license](https://img.shields.io/github/license/ArtBIT/bash-clam.svg)](https://github.com/ArtBIT/bash-clam) [![GitHub stars](https://img.shields.io/github/stars/ArtBIT/bash-clam.svg)](https://github.com/ArtBIT/bash-clam)  [![awesomeness](https://img.shields.io/badge/awesomeness-maximum-red.svg)](https://github.com/ArtBIT/bash-clam)

<h1><img src="/assets/clam.png" height="50"> CLAM</h1>

CLAM is a recursive acronym for "CLAM, Load A Module". CLAM is a simple package manager for Bash shell which helps you install and manage shell scripts and rc files from GitHub.

# Installation
```
git clone https://github.com/ArtBIT/bash-clam.git
source path/to/clam/init
```

# Usage

```
clam GitUsername/git-repo --exe some_script_from_that_repo
some_script_from_that_repo "is now an executable command"
```

# Environment
```bash
export CLAM_COMMAND_NAME=mollusk
# clam is registered as `mollusk` instead of `clam`
mollusk status
```

# License

[MIT](LICENSE.md)
