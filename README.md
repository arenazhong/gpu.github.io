# create new repo on github：gpu.github.io

# local command
```
npx create-next-app@latest --typescript gpu
package.json: 添加"export": "next export"到scripts
cd gpu && yarn dev # URL：http://localhost:3000
mkdir -p  .github/workflows
touch  .github/workflows/gh-pages.yml
git add .; git commit -m "."; git push origin main;
```