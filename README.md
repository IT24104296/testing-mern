echo "node_modules/
.env
dist/" > .gitignore

git init

git add .

git commit -m "initial commit"

git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git

git branch -M main
git push -u origin main




Base directory: .
Build command: cd frontend && npm install && npm run build
Publish directory: frontend/dist

VITE_API_URL=https://your-railway-url/api
