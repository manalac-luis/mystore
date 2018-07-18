echo "# mystore" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/manalac-luis/mystore.git
git remote set-url origin https://manalac-luis@github.com/manalac-luis/mystore.git
git push -u origin master
