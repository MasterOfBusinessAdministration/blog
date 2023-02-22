# blog
MBA Community's Blog


To load themes and other submodules

```
git submodule update --init --recursive # needed when you reclone your repo (submodules may not get cloned automatically)
```

To add a post
```
hugo new posts/post-name.md
```

To serve

```
hugo server
```

To publish
```
hugo
```

Remove large files from git history
```
git filter-branch --tree-filter 'rm -f filename.zip' HEAD
git push origin --force --all
```

Prune
```
git gc
git gc --aggressive
git prune

bfg -b 4M  # To remove all blobs from history, whose size is superior to 4Mb
git reflog expire --expire=now --all
```
