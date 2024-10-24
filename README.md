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
1. Launch the Git CLI using the terminal:
   ```bash
   1.1. Go to src/
   1.2. Execute "python git_CLI.py"
   ```

2. Launch the Streamlit front Git CLI:
   ```bash
   1.1. Go to src/st_front/
   1.2. Execute "streamlit run st_front.py"
   ```

## Future Implementations
- Implement functionality to handle merge conflicts.
- Enhance remote repository management to include fetching and pushing specific branches.
- Add a feature to stash changes temporarily.
- Implement support for SSH authentication for remote repositories.

## Contributing
Contributions are welcome! If you have suggestions or improvements, please open an issue or submit a pull request.

## Acknowledgments
- Thank you to the open-source community for providing tools and libraries that make development easier and more efficient.
