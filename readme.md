touch README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/arcadefx/gitplay.git
git push -u origin master

----------

 git branch
 git add readme.md
 vim index.py
 git commit -m "2nd commit"
 git push origin (save to master in this case)
 git checkout -b play-001  (create a new branch)
 git push origin play-001  (create a new branch part 2, switch to it -- only once)
 vim test.py 
 git add test.py  (add a file)
 git commit -am "added test.py"   (commit the file, note -am option)
 git branch   (see branch)
 git push origin  (push changes of current branch to repo)

