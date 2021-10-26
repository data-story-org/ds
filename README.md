Easy development setup for DataStory

### Prerequisites
* unix file system
* git installed
* ssh access to github
* yarn

### Installation
```
git clone git@github.com:data-story-org/ds.git
export PATH=$PATH:$(pwd)/ds
```
Now you have access to command `ds`. We will assume you have the following paths:
```
CODE_PATH=$HOME/Code
YARN_LINK_PATH=$HOME/.config/yarn/link/@data-story-org
```

if not, please create a file `.config` to set your own paths.


### Usage
Remove old datastory repos:
```bash
ds wipe
```

Install fresh repos:
```bash
ds install
```

Check status on existing repos:
```bash
ds status
```