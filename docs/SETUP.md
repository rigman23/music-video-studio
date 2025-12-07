# Setup Guide

This guide will help you set up the Music Video Studio project on your local machine.

## Prerequisites

Before you begin, ensure you have the following installed:

- Git (version 2.0 or higher)
- A GitHub account
- Python 3.8+ (recommended for AI features)
- FFmpeg (for video processing)

## Setting Up Your Repository

### For New Projects

If you're creating a new project based on this template:

1. **Initialize Git Repository**
   ```bash
   git init
   ```

2. **Add Files**
   ```bash
   git add .
   ```

3. **Create Initial Commit**
   ```bash
   git commit -m "Initial commit"
   ```

4. **Set Main Branch**
   ```bash
   git branch -M main
   ```

5. **Add Remote Repository**
   
   First, create a new repository on GitHub, then:
   ```bash
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   ```
   
   Replace `YOUR_USERNAME` with your GitHub username and `YOUR_REPO_NAME` with your repository name.

6. **Push to GitHub**
   ```bash
   git push -u origin main
   ```

### For Existing Repository

If you're cloning an existing repository:

1. **Clone the Repository**
   ```bash
   git clone YOUR_GITHUB_REPO_URL
   cd music-video-studio
   ```

2. **Install Dependencies**
   ```bash
   # Instructions will be added as project develops
   ```

## Project Structure

```
music-video-studio/
├── src/              # Source code
├── tests/            # Test files
├── docs/             # Documentation
├── examples/         # Example projects
├── README.md         # Project overview
└── .gitignore        # Git ignore rules
```

## Next Steps

After setting up your repository:

1. Configure your development environment
2. Install required dependencies
3. Review the README.md for usage instructions
4. Check the examples/ directory for sample projects

## Troubleshooting

### Common Issues

**Problem**: `fatal: remote origin already exists`
**Solution**: Remove the existing remote and add again:
```bash
git remote remove origin
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
```

**Problem**: Permission denied when pushing
**Solution**: Ensure you have proper authentication set up (SSH keys or Personal Access Token)

## Additional Resources

- [Git Documentation](https://git-scm.com/doc)
- [GitHub Guides](https://guides.github.com/)
- [Project README](../README.md)
