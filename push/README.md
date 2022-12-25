# Push

## Pushing a project is uploading code changes from a local repo (your computer) to a remote repo (GitHub)

### Can be seen as the following

```bash
(local) main -> (remote) main
```

### Pushing a Project from local to remote (first push)

1. adding remote origin (linking your remote)

```bash
git remote add origin https://github.com/<github-username>/<repo>.git
```

2. pushing a created project to a remote 

```bash
git push -u origin main
```
