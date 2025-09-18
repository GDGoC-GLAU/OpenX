# Contributing to OpenX Workshop

Thank you for participating in the OpenX Git/GitHub Workshop! This guide will walk you through the contribution process step by step.

## Prerequisites

Before you start, make sure you have:
- A GitHub account
- Git installed on your computer
- A text editor of your choice

## Step-by-Step Contribution Guide

### Step 1: Fork the Repository

1. Go to the [OpenX repository](https://github.com/GDGoC-GLAU/OpenX)
2. Click the "Fork" button in the top-right corner
3. This creates a copy of the repository in your GitHub account

### Step 2: Clone Your Fork

Open your terminal/command prompt and run:

```bash
git clone https://github.com/YOUR_USERNAME/OpenX.git
cd OpenX
```

Replace `YOUR_USERNAME` with your actual GitHub username.

### Step 3: Create Your File

1. Create a new file named `firstname_lastname.txt` (use your actual name)
2. Add the following content (customize with your information):

```
Name: Your Full Name
GitHub Username: @yourusername
Favorite Programming Language: Python
Fun Fact: Something interesting about you!
```

### Step 4: Add and Commit Your Changes

```bash
# Add your file to the staging area
git add firstname_lastname.txt

# Commit your changes with a descriptive message
git commit -m "Add firstname_lastname.txt - Workshop contribution"
```

### Step 5: Push to Your Fork

```bash
git push origin main
```

### Step 6: Create a Pull Request

1. Go to your forked repository on GitHub
2. Click "Compare & pull request" button
3. Add a title like: "Add [Your Name] - Workshop Contribution"
4. Add a description explaining your contribution
5. Click "Create pull request"

## Git Commands Quick Reference

| Command | Description |
|---------|-------------|
| `git clone <url>` | Clone a repository to your local machine |
| `git status` | Check the status of your working directory |
| `git add <file>` | Add file to staging area |
| `git add .` | Add all files to staging area |
| `git commit -m "message"` | Commit changes with a message |
| `git push origin main` | Push changes to remote repository |
| `git pull origin main` | Pull latest changes from remote |

## Best Practices

### Commit Messages
- Use present tense ("Add file" not "Added file")
- Keep the first line under 50 characters
- Be descriptive but concise

### File Naming
- Use lowercase letters
- Use underscores instead of spaces
- Follow the format: `firstname_lastname.txt`

### Content Guidelines
- Keep your content appropriate and professional
- Include accurate information
- Have fun with the "Fun Fact" section!

## Troubleshooting

### Common Issues

**Problem**: "Permission denied" when pushing
**Solution**: Make sure you're pushing to your fork, not the original repository

**Problem**: "File already exists" error
**Solution**: Make sure your filename is unique (use your actual name)

**Problem**: Merge conflicts
**Solution**: Ask for help during the workshop - we'll solve it together!

### Need Help?

- Raise your hand during the workshop
- Create an issue in this repository
- Ask your fellow participants

## What Happens Next?

After you create your pull request:
1. Workshop organizers will review your contribution
2. Your pull request will be merged into the main repository
3. Your name will appear in the contributors list
4. You've successfully made your first open source contribution! 🎉

## Additional Resources

- [Git Handbook](https://guides.github.com/introduction/git-handbook/)
- [GitHub Flow](https://guides.github.com/introduction/flow/)
- [Markdown Guide](https://www.markdownguide.org/basic-syntax/)

Remember: Making mistakes is part of learning! Don't be afraid to experiment and ask questions.

Happy contributing! 🚀
