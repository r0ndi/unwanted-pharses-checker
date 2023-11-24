# Pre commit script to prevent commit unwanted pharses

### Configuration
Edit global git config by:
```
git config --global --edit
```
Set pre-commit hook script in config:
```
[core]
   hooksPath = /path-to-this-project
```
#
Set privileges:
```
chmod +x /path-to-this-project/pre-commit
```
#
### Tips
To commit changes by bypassing the hook:
```
// console
git commit -m "commit msg" --no-verify

// via VSC
Source control -> more -> commit all
```
