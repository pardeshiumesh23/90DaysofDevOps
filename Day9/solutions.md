1. What is Git and why it is Important?\
Git is a distributed version control system (DVCS) that allows developers to manage and track changes to their source code and collaborate with others efficiently. It was created by Linus Torvalds in 2005 and has become one of the most widely used version control systems in the software development industry.\

   Here's why Git is important:\
   Version control\
   Collaboration\
   Branching and merging\
   Code review and quality control\
   Open source community\

2. What is difference Between Main Branch and Master Branch?\
   The terms "Main Branch" and "Master Branch" are often used interchangeably to refer to the primary branch in a Git repository that contains the stable and    
   production-ready codebase. However, there has been an ongoing discussion about the use of the term "Master" due to its historical association with slavery.\
   In response to this, many organizations and projects have adopted the term "Main" as a more inclusive and neutral alternative.\
   In essence, there is no technical difference between the "Main Branch" and the "Master Branch" in Git itself. It's more of a naming convention and a matter of 
   preference for the development community.\
   If you're starting a new project or repository, you can choose either "Main" or "Master" as the default branch name.\
   However, as a good practice, it is recommended to adopt "Main" to promote inclusivity and respect in the development community.\

3. Can you explain the difference between Git and GitHub?\
   Git:\
   Git is a distributed version control system (VCS). It is a tool used to track changes in source code or any set of files over time.\ 
   Git operates locally on a developer's machine and allows them to create, modify, and track branches, commits, and changes to the codebase.\
   It is designed to be lightweight, fast, and highly flexible, making it suitable for both small projects and large, complex software repositories.

   GitHub:

   GitHub is a web-based platform that provides hosting for Git repositories. It offers a centralized place where developers and teams can store, collaborate, and     manage their Git repositories.\
   It adds collaboration features on top of Git, such as issue tracking, pull requests, code review, and project management tools.\
   Developers can push their local Git repositories to GitHub, making it accessible to others in the team and facilitating collaboration.\
   GitHub also provides a web-based interface for browsing code, exploring repositories, and managing projects, making it easier for non-technical stakeholders to     participate in the development process.\

4. How do you create a new repository on GitHub? \
   Step 1: Click on New Repository. \
   ![Screenshot 2023-08-03 152602](https://github.com/pardeshiumesh23/90DaysofDevOps/assets/138001374/0ef2c915-9a09-4ef3-af18-113bbc62f5f1)

   step 2: Add the name of your new repository.
   ![Screenshot 2023-08-03 152423](https://github.com/pardeshiumesh23/90DaysofDevOps/assets/138001374/454faf56-3cf4-4969-b5df-99233eb13794)

5. What is difference between local & remote repository? How to connect local to remote?\
   Local Repository:\
   A local repository is a Git repository that exists on your local machine (computer). It contains all the version history, branches, and files related to your    
   project.\

   Remote Repository:\
   A remote repository is a Git repository that exists on a remote server, typically hosted by a service like GitHub, GitLab, Bitbucket, or any other Git hosting      provider.\

   To connect Local repository to Remote:\
   Create a remote repository: First, create an empty repository on the Git hosting service of your choice (e.g., GitHub, GitLab). Follow the instructions provided    by the hosting service to create the repository.

   Link your local repository to the remote: In your local repository, use the following command to add a remote URL. Replace <remote-name> with a meaningful name     like "origin," and <remote-URL> with the URL of the remote repository.
   ![Screenshot 2023-08-03 153836](https://github.com/pardeshiumesh23/90DaysofDevOps/assets/138001374/63d737d2-05ff-412f-8676-8509c477847f)
   
For example:
   ![Screenshot 2023-08-03 153903](https://github.com/pardeshiumesh23/90DaysofDevOps/assets/138001374/66c2d14f-7508-47b8-acdb-12a35e1da002)

Tasks: \
Task 1: Set your user name and email address, which will be associated with your commits. \
git config --global user.name \
git config --global user.email \

Task 2:\
Create a repository named "Devops" on GitHub. \
![Screenshot 2023-08-03 154727](https://github.com/pardeshiumesh23/90DaysofDevOps/assets/138001374/972ba4d7-a638-4e18-b5a0-e6ae9f2ca314)

Connect your local repository to the repository on GitHub.\
![Screenshot 2023-08-03 160249](https://github.com/pardeshiumesh23/90DaysofDevOps/assets/138001374/be28bb14-5900-4ed2-821a-99fec862eaec)

Create a new file in Devops/Git/Day-02.txt & add some content to it.\

![Screenshot 2023-08-03 160642](https://github.com/pardeshiumesh23/90DaysofDevOps/assets/138001374/fc1a0a4e-ac4e-4bee-8164-58df27f54637)

Push your local commits to the repository on Github.\
![Screenshot 2023-08-03 160952](https://github.com/pardeshiumesh23/90DaysofDevOps/assets/138001374/3604bffa-0ef1-48d6-8607-7a8d9ecc82fb)



