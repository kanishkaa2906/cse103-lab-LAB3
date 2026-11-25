# Setup Guide

## Prerequisites

- Python 3.8 or higher
- Git 2.x or higher

## How to Run

```bash
git clone https://github.com/vohragaurvi-beep/cse103-lab-LAB3.git
cd cse103-lab-LAB3
python3 src/main.py

Note: If you already have a `main.py` containing your lab work, copy its actual contents into `src/main.py` rather than replacing it with the sample code.

## Step 3. Update .gitignore

1. Find `.gitignore` in your repository.
2. Click the file.
3. Click the pencil icon.
4. Replace its contents with:

```gitignore
# Python bytecode
__pycache__/
*.py[cod]
*.pyo

# Environment files
.env
.venv/
venv/
ENV/

# Build and distribution
dist/
build/
*.egg-info/
.eggs/

# IDE / Editor settings
.vscode/
.idea/
*.swp
*.swo

# Operating system files
.DS_Store
Thumbs.db

# Logs and temporary files
*.log
*.tmp
*.bak
