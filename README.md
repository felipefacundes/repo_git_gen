# Repository Generator Script For GitHUB

This repository contains a powerful shell script designed to simplify the creation and initialization of GitHub repositories. It is an integral part of the [Shell Utils](https://github.com/felipefacundes/shell_utils), one of the most extensive collections of scripts and utilities aimed at improving user productivity and ease of use.

## Features
- Multilingual support for prompts and messages: Portuguese, French, German, Romanian, and English.
- Dependency checks for Git and GitHub CLI (gh).
- Automatic configuration of GitHub credentials.
- Validates repository descriptions with character limits and acceptable formats.
- Creates repositories locally and on GitHub, complete with initial commits.
- Configurable global Git settings through a custom configuration file.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/felipefacundes/repo_git_gen.git
   ```
2. Navigate to the script directory:
   ```bash
   cd repo_git_gen
   ```
3. Ensure the script is executable:
   ```bash
   chmod +x repo_git_gen
   ```

## Usage
Run the script with the following syntax:
```bash
./repo_git_gen <repository_name>
```
Replace `<repository_name>` with the desired name for your new repository.

### Example
```bash
./repo_git_gen my_project
```

This will:
1. Check for necessary dependencies (Git and GitHub CLI).
2. Prompt for GitHub authentication if not already configured.
3. Create a new repository directory locally and initialize it.
4. Push the repository to GitHub with the specified name.

## Prerequisites
- Git must be installed.
- GitHub CLI (gh) must be installed and configured.
- Linux or macOS environment (compatibility may vary with other systems).

For more information, explore the [Shell Utils](https://github.com/felipefacundes/shell_utils).
