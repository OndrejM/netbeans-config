# netbeans-config
Custom configuration for netbeans

Clone repo to the root of Netbeans installation:

```
REPOURL=https://github.com/OndrejM/netbeans-config.git &&
 git clone -n $REPOURL my-netbeans-config &&
 mv my-netbeans-config/.git/ .git &&
 rmdir my-netbeans-config/
```

Then apply changes:
```
 `git stash
```

To see what was changed:
```
 git stash show -p
```

To revert chanes:
```
git stash pop
```
