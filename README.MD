git init
new-item README.MD
git add .
git branch -M main
git remote add origin git@github.com:ynet2k/TodoApi.git
git push -u origin main
git branch dev
git push -u origin dev

dotnet dev-certs https --trust