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
- [YouTube tutorial](https://www.youtube.com/watch?v=G-EGDH50hGE)
- [Profile generator](https://rahuldkjain.github.io/gh-profile-readme-generator/)
- [Profile repository](https://github.com/EddieHubCommunity/awesome-github-profiles)
- [Profile examples](https://eddiehubcommunity.github.io/awesome-github-profiles/profiles)

### GitHub Documentation Samples
- [Awesome GitHub Profiles](https://github.com/EddieHubCommunity/awesome-github-profiles)
- [Shapash](https://github.com/MAIF/shapash)
- [Pandas](https://github.com/pandas-dev/pandas)
- [BCNN for Ocular Disease Classification](https://github.com/Ellie190/BCNN-for-Ocular-Disease-Classification)
- [Database Systems Tutor](https://github.com/Ellie190/Database_Systems_Tutor)
- [Google Trends Dashboard](https://github.com/Ellie190/Google-Trends-Dashboard)
- [Awesome Conformal Prediction](https://github.com/valeman/awesome-conformal-prediction)

### Git Configuration
- Set up your Git identity after creating a [GitHub](https://github.com/) account and installing [Git](https://git-scm.com/downloads)
```
 git config --global user.name "Your Name"
```

```
git config --global user.email "youremail@example.com"
```

### GitHub Repository
- **GitHub repository:** A GitHub repository is a storage space or container where you can store and manage your project's files, code, and related resources. 
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

### Push local project or code to GitHub
Assume you have a local project directory called `"my_project"` with some code files, and you want to push your changes to a remote repository on GitHub.
1. Initialize Git repository (if not already done):
```
cd /path/to/my_project
git init
```
2. Stage your changes - Suppose you made changes to two files, "index.html" and "style.css." To stage these changes, use:
```
git add index.html style.css
```
3. Commit your changes - Commit the staged changes with a descriptive commit message:
```
git commit -m "Added new homepage design"
```
4. Connect your local repository to a remote repository - Assuming you already created a new empty repository on GitHub called "my_project_repo," add the remote URL:
```
git remote add origin https://github.com/your-username/my_project_repo.git
```
5. Push your changes to the remote repository - Now, push the committed changes to the "main" branch (GitHub's default branch name) on the remote repository (substitute `master` branch with `main` branch if `master` branch is used):
```
git push origin main
```
If this is your first time pushing to the remote repository, Git may prompt you to enter your GitHub credentials (username and password or access token) to authenticate.

### Cheat Sheets
- [Markdown](https://www.markdownguide.org/cheat-sheet/)
- [.gitignore](https://github.com/kenmueller/gitignore)
- [Common Git commands](https://dev.to/ruppysuppy/git-cheat-sheet-with-40-commands-concepts-1m26)



