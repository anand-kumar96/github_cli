# Creating a Remote Repository URL Using GitHub CLI (gh)

To generate a remote repository URL without leaving the terminal, you can use GitHub's command-line interface (`gh`). Here's a step-by-step guide:

## Installation

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

## Authentication
Before creating a repository using `gh`, you need to authenticate with your GitHub account. You can do this by running the following command and following the prompts:

```bash
gh auth login
```
## Creating a Repository
Once authenticated, create a new repository on GitHub with the following command:
```https
gh repo create <repository_name>
```
Replace <repository_name> with the name of your repository.


