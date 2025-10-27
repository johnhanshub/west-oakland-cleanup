# Setting Up GitHub for West Oakland CleanUp

Follow these steps to get your project on GitHub:

## Step 1: Install Git (if not already installed)

Your system needs the Xcode Command Line Tools. A dialog should appear asking you to install them. Click "Install" and wait for the installation to complete.

Alternatively, you can run in Terminal:
```bash
xcode-select --install
```

## Step 2: Create a GitHub Account

1. Go to [GitHub.com](https://github.com)
2. Click "Sign up" in the top right
3. Create your account (it's free!)
4. Verify your email address

## Step 3: Create a New Repository on GitHub

1. Log into GitHub
2. Click the "+" icon in the top right corner
3. Select "New repository"
4. Name it: `west-oakland-cleanup` (or any name you prefer)
5. Make sure it's set to **Public** (or Private if you prefer)
6. **DO NOT** initialize with README, .gitignore, or license (we already have these)
7. Click "Create repository"

## Step 4: Initialize Git in Your Project

Open Terminal and run these commands:

```bash
# Navigate to your project folder
cd "/Users/john/DESIGN/VIBE CODING/West Oakland CleanUp"

# Initialize git
git init

# Add all files
git add .

# Make your first commit
git commit -m "Initial commit: West Oakland CleanUp project"

# Add your GitHub repository (replace USERNAME with your GitHub username)
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git

# Push your code to GitHub
git branch -M main
git push -u origin main
```

## Step 5: View Your Project on GitHub

Open your browser and go to:
```
https://github.com/YOUR_USERNAME/YOUR_REPO_NAME
```

Your project is now on GitHub! 🎉

## Tips

- **Commit often**: Make small, meaningful commits as you work
- **Write good commit messages**: Describe what changed and why
- **Create branches**: Use branches for new features or experiments
- **Push regularly**: Keep your GitHub repository up to date

## Common Git Commands

```bash
# Check status of your files
git status

# Add files to staging
git add .

# Commit changes
git commit -m "Your commit message"

# Push to GitHub
git push

# Pull latest changes
git pull
```

## Need Help?

- [GitHub Help Documentation](https://docs.github.com)
- [Git Documentation](https://git-scm.com/doc)
