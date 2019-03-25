https://ajaymore.github.io/dev/docs/server/cloud-server

### build command

```
git push --delete origin gh-pages
git branch -d gh-pages
git add website/build/dev && git commit -m "Initial dist subtree commit"
git subtree push --prefix website/build/dev origin gh-pages
```
