### build command

```
git push --delete origin gh-pages
git branch -d gh-pages
git add website/build/ajaymore.github.io && git commit -m "Initial dist subtree commit"
git subtree push --prefix website/build/ajaymore.github.io origin master
```
