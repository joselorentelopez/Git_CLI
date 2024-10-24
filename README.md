# Git CLI

## Overview
Git CLI is a command-line interface tool for managing Git repositories. Built with Python, it simplifies essential Git operations like initializing repos, creating and switching branches, committing changes, and syncing with remote repositories. This project aims to enhance version control efficiency for developers of all skill levels.

## Features
- **Set Working Directory**: Change the current working directory to any specified path.
- **Create New Repository**: Initialize a new Git repository in the current directory.
- **Branch Management**:
  - Create new branches
  - Show the list of available branches
  - Change to a specified branch
  - Delete existing branches
- **File Management**:
  - Show pending files and their statuses
  - Commit changes with a user-defined message
  - View commit history
- **Remote Repository Management**: Add and manage remote repositories.
- **Synchronization**:
  - Pull changes from the remote repository
  - Push changes to the remote repository

## Installation
To run this project, ensure you have Python 3.10 or later installed on your system. You can manage Python versions using [pyenv](https://github.com/pyenv/pyenv).

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. Install required dependencies (if any):
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Launch the Git CLI:
   ```bash
   python st_front.py
   ```

2. Use the following commands within the CLI to manage your Git repository:
   - Set your working directory:
     ```
     set_working_directory()
     ```
   - Create a new repository:
     ```
     create_new_repo()
     ```
   - Create a new branch:
     ```
     create_new_branch()
     ```
   - View the list of branches:
     ```
     show_branch_list()
     ```
   - Change to a different branch:
     ```
     change_branch()
     ```
   - Show pending files:
     ```
     show_pending_files()
     ```
   - Commit changes:
     ```
     commit_changes()
     ```
   - View commit history:
     ```
     show_commit_history()
     ```
   - Delete a branch:
     ```
     delete_branch()
     ```
   - Set a remote repository:
     ```
     set_remote_repository()
     ```
   - Pull changes from the remote repository:
     ```
     pull_changes()
     ```
   - Push changes to the remote repository:
     ```
     push_changes()
     ```

## Future Implementations
- Implement functionality to handle merge conflicts.
- Enhance remote repository management to include fetching and pushing specific branches.
- Add a feature to stash changes temporarily.
- Implement support for SSH authentication for remote repositories.

## Contributing
Contributions are welcome! If you have suggestions or improvements, please open an issue or submit a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- Thank you to the open-source community for providing tools and libraries that make development easier and more efficient.
