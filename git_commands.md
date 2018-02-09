$ git clone git@github.com:galler-alexander/mlcourse_open.git
$ cd mlcourse_open
$ git remote -v
$ git remote add upstream git@github.com:Yorko/mlcourse_open.git
$ git remote -v
$ git fetch upstream
$ git checkout master
$ git merge upstream/master

$ git mergetool

$ git commit -m "Merged upstream/master fixed conflict."

$ git push


#compare repos
$ git diff master upstream/master
