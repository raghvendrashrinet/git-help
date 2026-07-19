
- Compare specific branches:
```
git fetch origin  main          #  git fetch origin               
git diff main origin/main       # git diff local-branch origin/remote-branch
```

- Compare current branch against its upstream
```
git fetch
git diff @{upstream}   
```

- Compare current branch against the latest fetched commit:
```
git fetch
git diff FETCH_HEAD   
```
