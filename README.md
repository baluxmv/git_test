## Amazing Comments
This is Francisco's first gir project!


Hello Odin!


## Knowledge Check
### How do you create a new repository on GitHub?
- Log into your GitHub account
- Click the "+" button on the top right corner and select "New repository"
- Fill in the repository name, description, and choose between public or private visibility
- Click "Create repository"


### How do you copy a repository onto your local machine from GitHub?
- Navigate to the GitHub repository page
- Click the green "Code" button
- Copy the SSH URL provided
- Open your terminal and navigate to the desired directory
- Run the command `git clone <copied URL>`


### What is the default name of your remote connection?
The default name is "origin"


### Explain what `origin` is in `git push origin main`
- `origin` is a shorthand name for the remote repository URL
- It represents the main (or original) copy of your project on GitHub


### Explain what `main` is in `git push origin main`
- `main` is the name of the branch you are pushing your changes to
- It is the default branch on GitHub and typically represents the main development line


### Explain the two-stage system that Git uses to save files
- **Staging Area:** Think of this as a preparation zone. When you modify files, they don't automatically become 
part of your project's history. Instead, you use git add to selectively move files into the staging area. This 
allows you to group related changes and create meaningful snapshots.

- **Commit:**A commit is a permanent record of your project's state at a given moment. When you're ready to save a 
set of changes, you use `git commit` to create a snapshot of everything in the staging area. This snapshot 
is assigned a unique identifier (a hash) and includes a commit message describing the changes.
