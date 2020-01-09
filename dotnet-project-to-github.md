## Creating ASP.NET Web project on GitHub

1.  Sign in on github.com
2.  Create a new Public Repository with name `aspnet webapp`
    Use option "Initialize Repository with ReadMe"
    Use Option "GitIgnore" and Search for "VisualStudio"

3.  Open Git Bash and Goto directory `/c/users/$USERNAME/source/repos/`
    And clone your newly created GitHub Repository
    
    ```Bash
    $ cd /c/Users/$USERNAME/source/repos/
    $ git clone https://github.com/mahendra-shinde/aspnet-webapp
    ```
    NOTE: In GitBash, $username represents current logged in user

4.  Using Visual Studio, create a new ASP.NET Web Application `MyApp01` in folder
    `c:\users\%username%\source\repos\MyApp01`

    NOTE: %username% is system environment variable which always returns your current logged in username
          In case of an error replace it with your actual username.

5.  Use Team Explorer (Changes Menu) to Commit all changes to local Repository
6.  Use Team Explorer (Sync Menu) to Push all changes to GitHub

NOTE: For those who got ERROR in push from VS2017, the solution is:

-   Close VS
-   Delete (or rename) folder "C:\Program Files (x86)\Microsoft Visual Studio\2017{Community|Professional|Enterprise}\Common7\IDE\CommonExtensions\Microsoft\TeamFoundation\Team Explorer\Git"
-   Open VS and try to push a commit to a remote repo!

View original solution from [this link](https://developercommunity.visualstudio.com/content/problem/308898/error-encountered-while-pushing-to-the-remote-repo-3.html)