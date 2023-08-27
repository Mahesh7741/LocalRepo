GIT COMMANDS 
<BR>MAHESH SAVANT

<P>
steps to local file to remote file or GITHUB

STEP 1 : first create file go into file by using main line or --- command 


        cd file name

        mk newfilename

STEP 2 :

        git status

STEP 3 : 

        git add .

STEP 4 : 


        git commit -m "committed this file"

STEP 5 : 
    git push

    git push origin main
</P>



<h1> BRANCH GITHUB  STEPS</h1>

STEP 1: Check Which Branch you Work on 

        git branch

STEP 2: create new branch 

        git checkout -b brachname

STEP 3: move to other branch 

        git checkout branchname

STEP 4: Delete any branch 

        git branch -d branchname

STEP 5: Push Any other branch 

        git push origin branchname

STEP 6: Marging any Brach into main branch or master branch 

        git marge branch oppositebranchname

<p>
---------- other Method is PR (Pull Request)----------<br>
====> this method in Github app only.<br>
====>  Pull requset to main branch holder.<br>
====> holder reviwes the Code Than marge its .<br>
====> remote change --> Local Changes <br>
====> by using <span style="color:"green" ">PULL  COMMAND </span> <br>

        git pull origin filename

</p>

---------------------------------------------------<br>
<h1> how check commit </h1>

        git log 

<br>---------- <h1> Undoing Changes </h1>

case 1: staged changes

        git reset filename
        git reset

case 2: commited changes 

        git reset HEAD~1