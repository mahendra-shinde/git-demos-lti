## Azure DevOps and Cloud Questions

- What is Continuous Integration ?

        Developers should periodically / regularly `check-in` their code to the `central code repository`. The code would be then BUILD & TESTED on remote build servers. 

- What is Role of GIT in Continuous Integration ?

        `git` is one of the many `version control system` that can be used for central repository in continuous integration.

- Can Azure DevOps (TFS) Build Java Application ? If yes then what build tool it should use ?

        Yes, Uses `Maven`

- Can Azure DevOps (TFS) Build ASP.NET Application? If yes then what build tool it should use ?

        Yes, Uses VSBuild ( or MSBuild )

- Can Azure DevOps (TFS) Build Node Application? If yes then what build tool it should use ?

        Yes, Uses NPM ( Not exactly a build tool !)    

- What is Azure Repos ? How many Version control system does it support ?

        Azure Repos is a service that provides REMOTE code repository. It supports TWO version control systems: Git & TFVC (Team Foundation Version Control)

- Name any ONE distributed version control system

        Git & Mercurial are TWO distributed version control systems. Git became more popular that mercurial. Mercurial is supported on "BitBucket".

- Name any ONE centralized version control system

        SVN (Subversion) & TFVC are Centralized version control systems.

- Which command does download the changes made by OTHER users on REMOTE repository to your local repository ?

        GIT PULL

- Which command does UPLOAD the changes YOU MADE to REMOTE repository, so that OTHER users can download them?

        GIT PUSH

- What is “Git Commit” ? and when should I use this command ?

        Saves all the MARKED changes into LOCAL repository. The changes are MARKED by 'Git Add' command. So, Always use 'git commit' after 'git add'.

- What is “Git Clone” ? and when should I use this command ?

        Download the REMOTE repository as LOCAL repository. Use this command when you DO NOT HAVE local copy of REMOTE repository. 
        
        If you HAVE LOCAL copy, then use 'git pull' instead of 'git clone'

- Does Azure DevOps allows Build pipeline to use any external version control system / repository ?

        Azure DevOps allows external repositories like GitHub, BitBucket, Other External Git and even SVN.

- List at least TWO git repository host (providers) which can be configured with Azure DevOps pipeline.

        GitHub & BitBucket are Git Hosting providers supported by Azure DevOps.

- What is role of Azure Board in Azure DevOps

        An Agile Planning board, to add Work Items & Allocate tasks to team members. Also track the progress.

- In Build Pipeline, which step should appear first ? 1. Get Sources  or 2. Build Using VSBuild 

        Get Sources is FIRST, becouse Build using VSBuild requires source code.

- What are benefits of cloud ?

        Self Service
        Global Availibility
        Scaling 
        Cost (Pay as you Use)

- List any TWO cloud vendors ?

        Microsoft Azure, Amazon AWS, Google Cloud, IBM BlueMix, Oracle Cloud

- What is PaaS and Whom does it target ?

        PaaS: Platform As A Service provides Pre-Built environments to deploy your applications. Its targeted for "Developers"

- What is IaaS and Whom does it target ?

        IaaS: Infrastructure As A Service provides "IT Administrators" freedom to design environments as per custom requirements. Targeted at "IT Administrators/Operations"

- What is Public IP of a VM ?

        IP Address accessible from internet. Public IPs are CHARGED !

- How to Access a Windows VM from Azure ( Port Name or Number )

        Remote Desktop Protocol (RDP/3389) is Used for accessing windows VMs from Azure.

- What is Continuous Deployment ?

        Automating the process of deploying application to target environment (Local or Cloud).

- List any TWO Test Framework / Tool that can be integrated with Azure DevOps

        JUnit, NUnit, VSTest, Selenium etc can be integrated with Azure DevOps.

- What is Release in AzureDevOps ?

        A project artifacts ready for deployment are called "Release" in Azure DevOps". Once "Release" is ready, it can be "Manaully" or "Automatically" deployed at target enviornment.

-  What is Azure DevOps ?

        A SaaS (Software As A Service) from Microsoft for Managing Agile projects (Azure Boards), Providing the Remote (Hosted) Repositories (Azure Repos) and Setting up Continuous Integration and Deployment (Azure Pipelines)

        A Local install of Azure DevOps is available as "Azure DevOps Server" which was earlier known as "TFS" (Team Foundation Server).

        Azure DevOps was called "VSTS" (Visual Studio Team Services) till mid of 2018.

        Alternative to Azure DevOps are : Jira (Azure Boards) and Jenkins (Azure Pipelines)


