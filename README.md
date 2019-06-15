# hackforla-template
Possible template for Hack for LA

### Build and serve the website locally

This command starts the server locally. The server watches for changes to
the source files and rebuilds and refreshes the site automatically in your browser.

```bash
//enter command
```

## Incorporating changes from upstream

Your fork of this repository on GitHub, and your local clone of that fork, will
get out of sync with this (upstream) repository from time to time.

A few `git` commands is all it takes to get your local clone up to date.
Assuming you have a local clone with remotes `upstream` (this repo) and `origin`
(your GitHub fork of this repo):

```bash
# WARNING: this will erase local pending changes!
# commit them to a different branch or use git stash
git checkout master
git fetch upstream
git reset --hard upstream/master
```

Creating a new branch for feature/bugfix work now results in a clean, easy merge
down the line.

Now that local is up to date with `upstream`, update your GitHub fork with:

```bash
git push --force origin/master
```
