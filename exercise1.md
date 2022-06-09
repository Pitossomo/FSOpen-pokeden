Let's consider a Python developer who works on a team and wants to merge the changes made to a codebase. For this, he needs to make a pull request to the main branch, but some steps are required starting from the moment he forks the repo to make his own change to the existing code. When preparing to alter a existing codebase, the dev has to use the code pattern of that codebase, which is ensured by the lint tool used (eg. PyLint). It is also crucial to test its own code or, better yet, on the code resulting from the future merging. For this, we use tools as Selenium and unittest. We could make a fork of the main branch specifically to merge the new changes and then test it after the changes. Since Python is a interpreted language we do not have to worry about the build part, which consists in compiling the code in a executable format. 
Besides the solf-hosted Jenkins and the cloud-based GithubActions, some of the popular Continuous Integration tools are:
* AWS CodePipeline, cloud-based, easily integrated with other Amazon services
* Microsoft Azure DevOps Server, for .NET and Java apps and for users of other Microsoft's solutions
* Circle CI
TODO - Check for use cases for self-hosted and cloud-based enviroments