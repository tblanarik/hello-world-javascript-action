# hello-world-javascript-action

Followed directions from here: https://docs.github.com/en/actions/creating-actions/creating-a-javascript-action

#### Build
```bash
ncc build index.js --license licenses.txt
git add dist/index.js
git commit -m "..."
git tag -a -m "..." vX.Y
git push --follow-tags
```