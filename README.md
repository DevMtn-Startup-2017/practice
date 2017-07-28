# practice

1. All work should be done on your own branch. NEVER work directly on the master branch. 


2. To create a new branch, type:

         git checkout -b <branch-name>

3. To switch branches, type: 

        git checkout <branch-name>


4. You will push to your branch as you work. 

5. When changes get incorperated into the master branch you will need to update the master branch on your computer and the branch you are working on


        git checkout master
        git pull
        git checkout <branch-name>
        git add .
        git commit -m 'updating branch with master'
        git merge master

            (if there are conflicts, resolve them in your code editor. once all conflicts are resolved, type:
            
                git add .
                git commit -m 'fixed merge conflicts'
                git merge master
            
            )


6.  When you get to a point where your code is ready to be merged to the master, make sure to update your branch copy with the master (see code above) and then push your changes to your branch. 

    - Check with the team lead to make sure there are no other pull requests open and that your changes are ready to be merged to the master.

    - Once you get the ok, go to the repo on github.com, navigate to your branch, and press the "create pull request" button. This will create a request to merge your changes to the master branch. Have the project lead check the changes. If everything is ok they will approve the pull request and your changes will be merged with the master. 

    - After a pull request is completed the team should update their local copies of the master and merge that to their current branch. This will ensure they everyone is working on the most up to date version of the project and that their changes will work with all of the other changes already implemented. 