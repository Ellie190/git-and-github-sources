# git-and-github-sources
Learning materials on Git and GitHub

### Introduction
- Version control and collaboration are critical in software development.
- GitHub and Git Bash are fundamental tools for version control.

### Version control basics
- **Version control:**  Tracks changes in software development, enables collaboration, and provides a history of modifications
- **Challenges**
   - Conflicting code changes
   - Difficulty tracking changes
   - Potential loss of data
- **Solution:** Git and GitHub

### Git
- **Git:** A distributed version control system that:
     - Track changes to files and code
     - Manage changes to files and code
     - Record modifications to projects
     - Compare different versions of files and code
     - Revert to previous states
     - Allow collaborations
- **Benefits:**  Enables offline work, fast branching, and merging, and robustness

### Download Git
[Git SCM](https://git-scm.com/downloads)

### Git Bash
- **Git Bash:** A command-line interface for Git on Windows
- **Uses:**
   - **Git Operations:** Git Bash is primarily used for interacting with Git and performing version control tasks. You can use Git Bash to `initialize` a new Git repository, `clone` existing repositories, `create` and `switch` between branches, `stage` and `commit changes`, `push` and `pull` from remote repositories, and perform other Git operations.
   - **Command-Line Operations:** Git Bash provides a Unix-like command-line environment on Windows, allowing you to run a wide range of command-line operations and utilities. You can use it to navigate directories `(cd, ls)`, create and delete files or directories `(touch, mkdir, rm)`, edit files `(nano, vi)`, search for files `(find, grep)`, and execute various shell commands.
   - **Integration with Other Tools:** Git Bash can be used alongside other tools and utilities in the software development ecosystem. For example, you can use Git Bash to run package managers (such as npm or `pip`), build tools (like Make or Gradle), or other command-line interfaces required by your development workflow.

### GitHub
- **GitHub:** GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.
- **Get started with GitHub:** [GitHub Hello World](https://docs.github.com/en/get-started/quickstart/hello-world)
- **Various ways GitHub can be used:**
  1. **Version Control:** GitHub is primarily used for hosting Git repositories, providing version control for software development projects, tracking changes, and facilitating collaboration among developers.
  2. **Code Collaboration:** Developers can work together on projects by forking repositories, making changes in branches, and creating pull requests to propose and review code changes.
  3. **Code Review:** GitHub's pull request feature allows for detailed code reviews, enabling developers to provide feedback, discuss changes, and ensure code quality before merging.
  4. **Documentation:** GitHub offers support for markdown files, making it suitable for maintaining project documentation, READMEs, and wikis.
  5. **Sharing Code and Open Source:** GitHub is a popular platform for sharing open-source projects, allowing developers to collaborate on public projects and contribute to various software initiatives.
  6. **Community Engagement:** GitHub fosters a community around projects, allowing users to follow repositories, star projects, raise issues, and contribute to discussions.
  7. **Portfolio and Showcase:** Developers can use GitHub to showcase their projects, skills, and contributions to potential employers or collaborators.
  8. **Education and Learning:** GitHub can be used for educational purposes, as teachers can create repositories for course materials, assignments, and students' projects.
  9. **Data Hosting:** GitHub allows users to host data files, datasets, or static websites using GitHub Pages.
  10. **Integration with Tools:** GitHub integrates with numerous development tools and services, like project management platforms, code editors, chat applications, and code quality tools.

 
### GitHub Profile Creation Guide
- Profile creation steps
  1. Click on "New" to create a new repository.
  2. Choose a repository name that represents your profile. It's common to use your Git account name or user name as the repository name to make it easily identifiable. For example, if your Git account name is "johndoe," name the repository "johndoe" as well.
- [YouTube tutorial](https://www.youtube.com/watch?v=G-EGDH50hGE)
- [Profile generator](https://rahuldkjain.github.io/gh-profile-readme-generator/)
- [Profile repository](https://github.com/EddieHubCommunity/awesome-github-profiles)
- [Profile examples](https://eddiehubcommunity.github.io/awesome-github-profiles/profiles)

### GitHub Documentation Samples
- [Awesome GitHub Profiles](https://zzetao.github.io/awesome-github-profile/)
- [Shapash](https://github.com/MAIF/shapash)
- [Pandas](https://github.com/pandas-dev/pandas)
- [BCNN for Ocular Disease Classification](https://github.com/Ellie190/BCNN-for-Ocular-Disease-Classification)
- [Database Systems Tutor](https://github.com/Ellie190/Database_Systems_Tutor)
- [Google Trends Dashboard](https://github.com/Ellie190/Google-Trends-Dashboard)
- [Point Blank](https://github.com/rstudio/pointblank)

### Git Configuration
- Set up your Git identity after creating a [GitHub](https://github.com/) account and installing [Git](https://git-scm.com/downloads)
```
 git config --global user.name "Your Name"
```

```
git config --global user.email "youremail@example.com"
```
### Git Version
```
git --version
```

### GitHub Repository
- **GitHub repository:** A GitHub repository is a storage space or container where you can store and manage your project's files, code, and related resources. In version control systems, a repository is a data structure that stores metadata for a set of files or directory structure. 
- **GitHub repository naming convention:** A good GitHub repository name should be descriptive, concise, lowercase, use dashes or underscores, avoid special characters, and be unique.
- **Examples of good repository names:**
   - `awesome-website`
   - `python-utils`
   - `data-analysis-tool`
   - `my-project-v2.0`
   - `react-component-library`

### Common Git Commands
- Creating and cloning repositories
```
git init
```

```
git clone <repository-url>
```
- Basic workflow
```
git status
```

```
git add .
```

```
git commit -m "Your commit message here"
```

```
git push
```

```
git pull
```

```
git branch <branch-name>
```

```
git checkout <branch-name>
```

```
git checkout -b <branch-name>
```

```
git branch
```

### Common Unix-like Commands
Sure! Here's the updated table with an additional column that provides a brief explanation of how to use each command:

| Command  | Description                                       | How to Use                                     |
|----------|---------------------------------------------------|------------------------------------------------|
| `cd`     | Change directory                                 | `cd <directory>`                               |
| `pwd`    | Print working directory (show current directory) | `pwd`                                          |
| `ls`     | List files and directories in the current directory | `ls [options]`                             |
| `mkdir`  | Create a new directory                           | `mkdir <directory>`                            |
| `rm`     | Remove files or directories                      | `rm [options] <file/directory>`                |
| `cp`     | Copy files or directories                        | `cp [options] <source> <destination>`          |
| `mv`     | Move or rename files or directories              | `mv <source> <destination>`                    |
| `cd ..`  | Move one directory back                          | `cd ..`                                        |
| `cd ../../..`  | To move multiple directories back, you can chain the cd .. command as needed| `cd ../../..`  |



### Push local project or code to GitHub
Assume you have a local project directory called `"my_project"` with some code files, and you want to push your changes to a remote repository on GitHub. For simplicity, ensure your local directory project name is the same as the remote GitHub repository

- [Adding locally hosted code to GitHub](https://docs.github.com/en/migrations/importing-source-code/using-the-command-line-to-import-source-code/adding-locally-hosted-code-to-github)

### Branch naming 
When working with GitHub branches, it's essential to follow a consistent and meaningful naming convention to maintain clarity and organization within the repository.
1. **Feature Branch**:
   - Branch name: `feature/add-user-authentication`
   - Description: This branch is used to develop the user authentication feature.

2. **Bugfix Branch**:
   - Branch name: `bugfix/fix-login-crash`
   - Description: This branch is used to fix a bug that causes the application to crash during login.

3. **Hotfix Branch**:
   - Branch name: `hotfix/fix-security-issue`
   - Description: This branch is used to address a critical security issue.

4. **Release Branch**:
   - Branch name: `release/v2.1.0`
   - Description: This branch is used to prepare for the v2.1.0 release of the software.

5. **Main Branch**:
   - Branch name: `main`
   - Description: The default branch in the repository where the stable code resides.

6. **Other Branches**:
   - Branch name: `docs/update-readme`
   - Description: This branch is used to make updates to the project documentation, particularly the README file.

   - Branch name: `refactor/improve-performance`
   - Description: This branch is used to refactor the codebase to improve performance.

   - Branch name: `test/add-unit-tests`
   - Description: This branch is used to add new unit tests to improve code coverage.

```
git checkout -b feature/add-new-feature
```


### Cheat Sheets
- [Markdown](https://www.markdownguide.org/cheat-sheet/)
- [.gitignore](https://github.com/kenmueller/gitignore)
- [Common Git commands](https://dev.to/ruppysuppy/git-cheat-sheet-with-40-commands-concepts-1m26)

### Videos 
- [How to Compare and Create Pull Requests on GitHub](https://www.youtube.com/watch?v=K-pI_qSKDfo)



