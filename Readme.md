This is a sample Git Repository which I used to implement the merge strategy

* Create a local project and init
   * git init
* Add all the files we need to push
   * git add --all
* Check the status of the files
   * git status
* Commit the changes with the message
  *  git commit -m 'Initial Commit'
* Push the changes to the remote branch
  * git push -u origin main
* To check the branch you are working on
  * git branch
* Create a development branch from main
  * git branch development - creates a new branch locally
  * git checkout development - moves our existing workspace to development
* Make changes to the workspace and push that to the remote
  * git add --all
  * git commit -m 'Initial Development Commit'
  * git push origin development
* Create 2 new branches feature1 and feature2
  * git branch feature1
  * git branch feature2
* Make changes to feature1 and push it to remote
  * git checkout feature1
  * add a new file 'HelloWorldfeature1.java'
  * git add --all
  * git commit -m 'Changes to feature1'
  * git push origin feature1
* Create a pull request and merge changes from feature 1
* Make changes to feature2 and push it to remote
  * git checkout feature2
  * add a new file 'Hellowordfeature2.java'
  * git add --all
  * git commit -m 'Changes to feature2'
  * git push origin feature2
* Create a pull request and merge changes from feature 1
* Get the git log to see branches and merges
  * git log --oneline
* Revert the feature1 branch from development branch
  * git checkout development
  * git log --oneline --graph
  * Get the hashcode for the merge request
  * git revert -m 1 $mergeHashCode
* Get the git log in graphmode to see branches and merges
  * git log --oneline --graph
  
