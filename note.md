git init
echo "text" >> file.ext
git add file.ext
git commit -m "message commit"
git push -u origin main
git branch -M branchx
git remote rm origin
git remote add origin https://github.com/lamlhb03/javaapp.git
