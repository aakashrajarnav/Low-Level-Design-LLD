create a new repository on the command line
echo "# Demo" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/aakashrajarnav/Demo.git
git remote set-url origin https://github.com/aakashrajarnav/Low-Level-Design-LLD.git
git push -u origin main
