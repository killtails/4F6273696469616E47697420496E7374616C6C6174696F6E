---
tags:
  - obsidian
  - GitHub
---
# Downloads
[Obsidian](https://obsidian.md/download)
[GitHub Desktop](https://desktop.github.com)
[GIT SCM CLI](https://git-scm.com/downloads)
# Instructions
1. Download and Install [Obsidian](https://obsidian.md/download)
	1. Make a new Vault
	2. Make a new note
2. Make an account on [GitHub](https://github.com)
3. Download and Install [GitHub Desktop](https://desktop.github.com)
	1. Sign in to GitHub
	2. Authorize GitHub Desktop
	3. Configure Git (Use default options)
	4. Create New Repository
		1. Change Local Path to your Obsidian Vault
	5. Publish Repository to GitHub (Keep Code public or private)
	6. On browser check your repositories on GitHub to make sure they've been published
	7. Stop here if you want to manually push your changes. To automate this continue on.
4. Open Obsidian and Enable Community Plugins
	1. Search for Git (by Denis Olehov aka Vinzent03)
5. Download and Install [GIT SCM CLI](https://git-scm.com/downloads)
# What is Obsidian?
Obsidian.md is a popular note-taking and knowledge management application. It is designed to help users organize and connect their thoughts, ideas, and notes in a flexible and interconnected manner. Obsidian is often referred to as a "second brain" tool due to its focus on building a knowledge graph of interconnected notes.

Key features of Obsidian.md include:

1. **Markdown Support:** Obsidian uses Markdown, a lightweight markup language, for note formatting. This makes it easy to create well-structured and readable notes with plain text.

2. **Bi-directional Linking:** One of the standout features of Obsidian is its support for bi-directional linking. This means that if you create a link from one note to another, Obsidian automatically creates a backlink from the second note to the first. This helps in creating a web of interconnected thoughts.

3. **Graph View:** Obsidian provides a graph view that visually represents the relationships between your notes. This can be useful for understanding the connections and patterns in your knowledge base.

4. **Local Storage:** Obsidian stores your notes as plain text files on your local machine. This gives users control over their data and allows them to use their preferred cloud storage or version control systems.

5. **Customizable:** Users can customize the Obsidian experience by creating custom themes, plugins, and using various settings to tailor the application to their preferences.

6. **Tags and Categories:** You can organize your notes using tags and categories, making it easier to find and navigate through your knowledge base.

Obsidian.md is widely used by students, researchers, writers, and knowledge workers for personal and professional note-taking and knowledge management. It has gained popularity for its focus on simplicity, flexibility, and the ability to foster creative thinking by encouraging non-linear connections between ideas.
## Installing Obsidian
1. Download [Obsidian](https://obsidian.md/download) and run the installer.
## Vaults
In Obsidian, a "vault" refers to the directory or folder where your notes are stored. It contains all the Markdown files that make up your collection of notes. When you create or open a vault in Obsidian, you are essentially working within that specific directory, and Obsidian treats all the Markdown files within that directory as part of your knowledge base.

To create a new vault or open an existing one in Obsidian, you typically choose a directory on your computer where you want to store your notes. Once a vault is created or opened, you can start creating and organizing your notes within that specific directory. 

- After installing Obsidian, you are given the option to
	- **Create new vault**
		- Creates a new vault. 
	- **Open folder as vault**
		- If you have existing vaults or compatible notes.
	- **Open vault from Obsidian Sync**
		- If you have an existing Obsidian Sync Account you can use this option to connect and sync your notes.
## <span style="color: green;">Create a new vault in obsidian.</span>
## Creating Notes
After creating a vault you can now start creating notes. Notes are notes, you can write important stuff there.

1. To create a new note look for the "pen and paper" icon at the top left of the application and click on it.
![[5.png|400]]
2. A new "Untitled" note should open. Give it a name, you can always change it later. ![[6.png]]


# What is Git
Git is a distributed version control system (VCS) designed to track changes in source code during software development. It allows multiple developers to collaborate on a project and manage their codebase efficiently. Git was created by Linus Torvalds in 2005 and has become the de facto standard for version control in the software development industry.

Key features of Git include:

1. **Distributed Version Control:** Git is a distributed version control system, meaning that each developer has a complete copy of the entire repository on their local machine. This decentralization allows developers to work independently and without constant access to a central server.

2. **Branching and Merging:** Git makes branching and merging easy. Developers can create branches to work on specific features or fixes without affecting the main codebase. Once the changes are complete, branches can be merged back into the main branch.

3. **History Tracking:** Git maintains a detailed history of changes made to the codebase. Each commit is recorded with information about the author, timestamp, and a unique identifier. This history is valuable for understanding how the code has evolved over time.

4. **Staging Area:** Git uses a staging area (also known as the "index") to allow developers to selectively choose which changes to include in the next commit. This provides flexibility and control over the commit process.

5. **Fast and Efficient:** Git is designed to be fast and efficient, even with large codebases. This is achieved through techniques such as delta compression and storing data as snapshots.

6. **Integrity and Security:** Git ensures the integrity of the codebase by using cryptographic hash functions to generate unique identifiers (SHA-1 hashes) for each commit. This helps prevent data corruption and ensures the security of the versioned data.

7. **Collaboration:** Git facilitates collaboration among developers by providing mechanisms for sharing changes between repositories. Developers can push and pull changes from remote repositories, making it easy to work on projects with distributed teams.

8. **Open Source and Extensible:** Git is an open-source project, and its source code is freely available for inspection and modification. Additionally, Git is extensible, allowing users to customize their workflows and integrate with other tools.

Git is commonly used in conjunction with hosting platforms like GitHub, GitLab, and Bitbucket, which provide centralized repositories, collaboration features, and additional tools for project management. The combination of Git and these hosting platforms has become a standard practice in modern software development.

# What is GitHub
GitHub is a web-based platform that provides hosting for software development and version control using Git. It offers a range of collaborative features for teams and individuals working on software projects. GitHub is widely used for open-source development but is also utilized by private teams for proprietary software projects. Here are some key aspects of GitHub:

1. **Version Control:**
   - GitHub uses Git, a distributed version control system. Version control helps teams manage and track changes to their codebase, allowing multiple developers to work on a project simultaneously.

2. **Repository Hosting:**
   - A repository, or repo, is a container that holds a project and all its files, including the revision history. GitHub provides a platform for hosting Git repositories, making it easy for developers to collaborate and contribute.

3. **Collaboration:**
   - GitHub facilitates collaboration among team members. Developers can work on their individual branches and propose changes to the main codebase through pull requests. Issues, discussions, and project boards are also features that enhance collaboration.

4. **Pull Requests:**
   - Developers use pull requests to propose changes to the main codebase. This includes new features, bug fixes, or any other modifications. Pull requests are reviewed by other team members before merging.

5. **Issue Tracking:**
   - GitHub provides an issue tracking system to manage tasks, enhancements, and bugs for software projects. Issues can be assigned, labeled, and linked to code changes, making it easier to coordinate work.

6. **GitHub Actions:**
   - GitHub Actions is a feature that enables automation of workflows within the GitHub platform. It allows developers to define custom build and deployment processes, automated testing, and more.

7. **Wikis and Pages:**
   - GitHub provides built-in wikis and GitHub Pages for documentation. Teams can create and maintain documentation directly within their repositories.

8. **Social Coding:**
   - GitHub has a strong social aspect, allowing users to follow projects, developers, and organizations. Users can also star repositories to show appreciation or interest in a project.

9. **Open Source Contributions:**
   - GitHub is a hub for open-source development, and many open-source projects are hosted on the platform. Developers can contribute to existing projects by submitting pull requests.

10. **Security Features:**
    - GitHub provides security features such as vulnerability alerts, code scanning, and Dependabot to help developers identify and address potential security issues in their code.

GitHub is widely used in the software development community, and its popularity stems from its user-friendly interface, powerful collaboration features, and its role as a central hub for open-source projects.
## What is GitHub Desktop
Download: [GitHub Desktop](https://desktop.github.com)
GitHub Desktop is a graphical user interface (GUI) client for Git that simplifies the process of using Git and GitHub. It is designed to provide a more user-friendly experience, especially for those who may be less comfortable with command-line interfaces. GitHub Desktop is available for both Windows and macOS, and it allows users to interact with Git and GitHub repositories through a visual interface.

Key features of GitHub Desktop include:

1. **Graphical Interface:** GitHub Desktop provides a visual representation of your Git repository's history, branches, and changes. This graphical representation makes it easier for users to understand and manage their version control activities.

2. **Easy Repository Management:** Users can clone repositories from GitHub or other remote locations, create new repositories, and manage existing repositories directly from the GitHub Desktop interface.

3. **Branching and Merging:** GitHub Desktop simplifies the process of creating and managing branches. Users can easily create new branches, switch between branches, and merge changes visually.

4. **Committing Changes:** Users can stage and commit changes to their local repository directly from the GitHub Desktop interface. The application provides a clear view of the changes made to files and allows users to write commit messages.

5. **Syncing with GitHub:** GitHub Desktop enables users to push changes to GitHub or pull changes from GitHub with a simple click. This makes it easy to synchronize local changes with the remote repository.

6. **Collaboration:** Users can view and participate in discussions (issues and pull requests) directly within GitHub Desktop. This integration helps developers stay connected with the collaborative aspects of GitHub.

7. **Cross-Platform Support:** GitHub Desktop is available for both Windows and macOS, providing a consistent experience across different operating systems.

While GitHub Desktop is a powerful tool for many users, particularly those who prefer a GUI over the command line, it's worth noting that more advanced Git operations may still require the use of the command-line interface. GitHub Desktop is often recommended for beginners and those who are just getting started with version control and collaboration using Git and GitHub.
# What is Git-SCM
Download: [GIT SCM CLI](https://git-scm.com/downloads)

"Git SCM" stands for "Git Source Code Management" or "Git Software Configuration Management." It is a term that is often used to refer to the Git software and tools that enable source code management using the Git version control system.

"Git" is the version control system, while "Git SCM" often refers to the broader concept of source code management using Git, including the tools and practices associated with it.

When people mention "Git SCM," they are typically referring to the broader concept of source code management with Git, including the tools, commands, and practices associated with using Git for version control. The official website for the Git version control system, where you can find documentation, download the Git software, and access other resources, is often referred to as "Git SCM" or simply "Git."

In practice, when developers or users say they are installing or using "Git SCM," they are likely talking about obtaining the Git software for their system to start using Git for version control. The official website for Git, where you can download the Git software, is "https://git-scm.com/." From this site, you can access documentation, guides, and other materials to help you get started with Git for source code management.