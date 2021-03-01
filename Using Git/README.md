
**Ohjelmistotuotanto**\
**Exercise 1**\
**Using Git**

In this exercise, you elaborate on Git. First, you’ll need to imagine a small software application project to work with. Of course, you can also use one of your own projects if there is no security or privacy issues involved. You’ll also need to create your own GitHub or BitBucket project in case you don’t already have one.
Embed your theory answers, drawings, codes and screenshots directly into this document. Always immediately after the relevant question. Return the document into your return box in ~~the Optima~~ itsLearning platform by the deadline.
The maximum number of points you can earn from this exercise is 10. Each finished task is worth of 1 point.
This exercise must be done individually or in pairs. Remember to return the document into ~~the Optima~~ itsLearning return box by the agreed deadline.

### 1. Explain what for what Git version control is meant for. List also the main benefits of using version control in application development ###

  Version control is a system that records changes to a file or set of files over time so  that you can recall specific versions later. Git is a distributed version-control system originally designed for coordinating work among programmers cooperating on source code during software development. [[1]](https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control)

  Git is the established VCS thats being used by most of todays developers.

### 2. Install Git on your local computer. Document the process with screenshots and/or text ###

  On Mac or Linux distribution you can easily check if git is installed by typing

  `$ git --version`

  on your terminal. For example my terminal prompts an answer:
  
  ```
  $ git --version
  $ git version 2.21.1 (Apple Git-122.3)
  ```

  If you don’t have Git installed already, it will prompt you to install it. 
  
  For up to date versions and/or installing Windows version there's a good instructions found at Gits own documentation [here](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git). 

### 3. Explain the following Git and version control related concepts:
  
- A working directory

  You should think of the working directory (also commonly referred to as the “working tree”) as a sandbox, where you can try changes out before committing them to your staging area (index) and then to history. The other two trees (they being **The HEAD** and **The Index**) store their content in an efficient but inconvenient manner, inside the .git folder. The working directory unpacks them into actual files, which makes it much easier for you to edit them. [[2]](https://git-scm.com/book/en/v2/Git-Tools-Reset-Demystified#_the_working_directory)

- A staging area

  Staging Area or "the index" is what Git looks at when you run `git commit`. So you code what ever you are coding at the sandbox and then stage your saved changes (or add new files) to your proposed next commit.

- A local repository

  If you have a project directory that is currently not under version control and you want to start controlling it with Git you need to navigate to that project’s directory and run `git init`.
  After the initialization a local repository is created. `git init` creates a new subdirectory named .git that contains all of your necessary repository files — a Git repository skeleton. [[3]](https://git-scm.com/book/en/v2/Git-Basics-Getting-a-Git-Repository#_initializing_a_repository_in_an_existing_directory)

- A remote repository

  If you wish to use Git to its Fullest Potential and want to collaborate on any Git project, you need to know how to manage your remote repositories. Remote repositories are versions of your project that are hosted on the Internet or network somewhere. Managing remote repositories includes knowing how to add remote repositories, remove remotes that are no longer valid, manage various remote branches and define them as being tracked or not, and more. In this section, we’ll cover some of these remote-management skills. [[4]](https://git-scm.com/book/en/v2/Git-Basics-Working-with-Remotes#_remote_repos)

- A commit

  Git commit command is the main function for saving changes to local repository safely. Commit takes a snapshot of the project and treats it as a version. [[5]](https://www.bitdegree.org/learn/git-commit-command)

- A branch

  Branching in Git is a function that is used to create an independent, similar copy of the current repository for different usage requirements. For me branching and what is a branch is best to understand by thinking Git Feature Branch Workflow.

  > The core idea behind the Feature Branch Workflow is that all feature development should take place in a dedicated branch instead of the master branch. This encapsulation makes it easy for multiple developers to work on a particular feature without disturbing the main codebase. It also means the master branch will never contain broken code, which is a huge advantage for continuous integration environments. [[6]](https://www.atlassian.com/git/tutorials/comparing-workflows/feature-branch-workflow)

  So you make a copy (new `branch`) of the current version (`master`) of the product and start developing a new feature there. When you're finished you create a MR that eventually ends up being merged to the "new" master. Different developers can code different features same time and Git makes sure that it's easy for individual developer to compare the developed work to "released" product (in this case the master branch is released product). This comparison makes it much easies and saver to add new code to up to date codebase without fear of breaking up anything big. And even if you do, there's always version control so you can always roll back to previous  versions.

### 4. Initialize one of your programming projects in your local computer as git project. Display it status. Take a screenshot of the status message. ###

### 5. Write a short example of a .gitignore file. What is the purpose of that file? When you should add it? ###

You can use .gitignore to for example hide project dependencies.

A dependency, in software development, is a separate program or piece of code that is required for the operation of the software you are trying to run. You don't write (copy+paste) or maintain that code yourself, but rather install and/or update it via package management system and afterwards rely on that codebase when writing something based on that code. 

So you need the dependency for your code to work (hence you depend it) but because it comes as a separate package there's no point adding it to your codebase. The downside adding these dependencies to your project would be that they are rather big and can swallow up your project rather quickly. And it would be a copy+paste that particular version of the dependency. What happens when dependency gets updated. It makes much more sense to exclude these's depency files from the version control and rather point to them via separate instruction. In node projects this file is called package.json file.

### 6. Work locally with working area and staging area and make a few commits. Pay special attention on good commits’ comments. Take screenshots documenting your working process. Take also a screenshot of your git log ###

### 7. Create an account to GitHub or BitBucket. Take a screenshot that proofs that you have an account. Explain also what GitHub and BitBucket are ###

### 8. Push the contents of your local Git repository to your GitHub or BitBucket. Document the commands you used here. Add also a screenshot documenting your code on Net. Imagine that you were another user working on the project. How would you get the remote repository from GitHub or BitBucket on your own computer? Give the Git command ###

### 9. Use branches to work with your code. Explain the benefits of using branches. Give also the Git commands you used. Make also certain that you merge at least one branch to another. Document also this command or command chain here ###

### 10. What are pull requests? What are the benefits they can offer? Give a scenario of using pull requests. Take also a screenshot from you GitHub or BitBucket account that proves your capability to create and work with them ###