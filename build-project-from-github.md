## Build project from GitHub on Azure DevOps

1.  Sign in on dev.azure.com
2.  Create new PUBLIC project 
3.  Goto `Azure Pipelines` and click on `New Pipeline`
4.  Choose link `Use Classic Editor` (At the bottom of page).

![alt text](./images/build-1.png "Build step1")

5. Choose Source control "GitHub" and then Use "Authorize using GitHub" button (You need your GitHub User credentials)

![alt text](./images/build-2.png "Build step2")

6.  Now, choose your repository name and branch

![alt text](./images/build-3.png "Build step3")

![alt text](./images/build-4.png "Build step4")

7. Choose from template "ASP.NET" and click "Apply"

![alt text](./images/build-5.png "Build step5")

8.  IN First screen locate option `Path to solution or package.config` and use '...' button to choose .sln file.  

![alt text](./images/build-6a.png "Build step6a")

9.  Choose the Solution 

![alt text](./images/build-6.png "Build step6")

10. Finally use `Save & Queue` button to test FIRST build for this pipeline.

![alt text](./images/build-7.png "Build step7")

11. The Output should be:

![alt text](./images/build-8.png "Build step8")

