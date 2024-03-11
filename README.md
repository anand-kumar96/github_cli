# Creating a Remote Repository URL Using GitHub CLI (gh)

To generate a remote repository URL without leaving the terminal, you can use GitHub's command-line interface (`gh`). Here's a step-by-step guide:

## 1. Installation

If you haven't already installed `gh`, you can do so by following the installation instructions provided on GitHub's website: [GitHub CLI Installation](https://cli.github.com/).
### Or Run command
for window
```https
winget install --id GitHub.cli
```
for mac
```https
brew install gh
```

## 2. Authentication
Before creating a repository using `gh`, you need to authenticate with your GitHub account. You can do this by running the following command and following the prompts:

```bash
gh auth login
```
## 3. Creating a Repository
Once authenticated, create a new repository on GitHub with the following command:
```https
gh repo create <repository_name>
or
gh rep new
```
Replace <repository_name> with the name of your repository.

## 4. Retrieving the Remote Repository URL
After creating the repository, gh will provide you with information about the newly created repository, including its URL. You can capture this URL for later use.
## Example Usage

### Authenticate with GitHub
```https
gh auth login
```
### Create a new repository
```https
gh repo create my_project
or
gh repo new
```
### Move into the new directory
```https
cd my_project
```
### Initialize Git repository
```https
git init
```
### Add files
```https
git add .
```
### Commit changes
```https
git commit -m "Initial commit"
```
### Switch to the main branch
```https
git checkout -b main
```
### Add remote repository (origin)
```https
git remote add origin <remote_repository_url>
```
Make sure to replace <remote_repository_url> with the URL of your remote repository (e.g., https://github.com/username/repositoryname.git).

### Push to the remote repository
```https
git push origin main
```
