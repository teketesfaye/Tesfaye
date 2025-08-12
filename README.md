## Initial Setup & Configuration

### Configure Git with Personal Account
```bash
# Set global username and email
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"

# Set default branch name
git config --global init.defaultBranch main

# Check current configuration
git config --list

# Configure for specific repository only (remove --global)
git config user.name "Your Name"
git config user.email "your.email@example.com"
