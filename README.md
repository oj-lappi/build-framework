build tools
===================================

## worklist
if worklist.conf=`{default":{"type":"github","user":"oj-lappi"}}`
get list of repositories: for user oj-lappi from github.com

## worklist -t github -u oj-lappi
get list of repository addresses to start working on from github.com

## Future syntax
## worklist -t=github --cached -u=oj-lappi
get list of repository names from local cachefile

### build-git-tree
auto build project into commits with timestamps and add header to commit messages including test data and commit hash for validation.
Also writes git hashes with data into database for traceability & logging.

### qnd 
reads in and links selected files into configured directory from git repo.

### pull-install
runs git pull + build, used by qnd
