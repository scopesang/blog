…or create a new repository on the command line
echo "# blog" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:scopesang/blog.git
git push -u origin main