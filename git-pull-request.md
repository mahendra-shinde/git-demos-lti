## Git Pull Requests!

1. Form a TEAM of 5/6 individuals.

    - Every team member MUST HAVE github.com account.

    - Every member should provide his/her git account name to team leader.


2.  Team Leader should then use his/her GitHub account to create
    a public repository with README file.

3.  Once repository is created, goto "Settings" tab and choose
    "Collaborators" and enter GitHub account names of all your team members. Send them invites.

4.  All team members should now accept the invite from their registered email address.

5.  Every team member should now CLONE remote repository in their local system. Ask Team Leader to share the repository URL.

    ```cmd
    $ cd /c/my-repos/
    $ git clone https://github.com/mahendra-shinde/my-collaboration-project.git
    $ cd my-collaboration-project
    $ git status
    ```

6.  Now, create a branch with your name and add files

    ```cmd
    $ git checkout -b mahendra
    $ code file-mahendra.txt
    $ git add .
    $ git commit -m "file added"
    $ git push -u origin mahendra
    ```

    NOTE: Last command requires branch name (replace mahendra with your name/branch-name)

7.  Open remote repository in github.com and use button "Compare & Pull request"

8.  Now, request your Team Leader to accept your pull request.