create a new repository on the command line
=================================================================
echo "# forgetcommand" >> README.md

git init

git add README.md

git commit -m "first commit"

git remote add origin git@github.com:evanslight/forgetcommand.git

git push -u origin master

