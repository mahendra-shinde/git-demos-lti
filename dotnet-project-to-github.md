## Creating ASP.NET Web project on GitHub

1.  Sign in on github.com
2.  Create a new Public Repository with name `aspnet webapp`
    Use option "Initialize Repository with ReadMe"
    Use Option "GitIgnore" and Search for "VisualStudio"

3.  Open Git Bash and Goto directory `/c/users/$username/source/repos/`
    And clone your newly created GitHub Repository
    
    ```Bash
    $ cd /c/Users/$username/source/repos/
    $ git clone https://github.com/mahendra-shinde/aspnet-webapp
    ```
    NOTE: In GitBash, $username represents current logged in user

4.  Using Visual Studio, create a new ASP.NET Web Application `MyApp01` in folder
    `c:\users\%username%\source\repos\MyApp01`

    NOTE: %username% is system environment variable which always returns your current logged in username
          In case of an error replace it with your actual username.

5.  Use Team Explorer (Changes Menu) to Commit all changes to local Repository
6.  Use Team Explorer (Sync Menu) to Push all changes to GitHub