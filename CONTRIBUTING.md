# Contributing Guidelines

Thank you for contributing to the DevOps-Elective repository! This guide will help you contribute effectively.

## Getting Started

1. **Fork the repository** to your GitHub account
2. **Clone your fork** locally:
   ```bash
   git clone https://github.com/YOUR_USERNAME/DevOps-Elective.git
   cd DevOps-Elective
   ```
3. **Add the upstream remote**:
   ```bash
   git remote add upstream https://github.com/Gokulan-SK/DevOps-Elective.git
   ```

## Making Contributions

### For Experiments

1. Create a new branch for your experiment:
   ```bash
   git checkout -b experiment/your-experiment-name
   ```

2. Create your experiment directory:
   ```bash
   mkdir experiments/your-experiment-name
   cd experiments/your-experiment-name
   ```

3. Include these files in your experiment:
   - `README.md` - Experiment overview and instructions
   - `setup.sh` - Setup script (if applicable)
   - Configuration files and code
   - `results.md` - Your findings and results

### For Projects

1. Create a project directory under `projects/`
2. Include comprehensive documentation
3. Provide clear setup and deployment instructions
4. Document architecture and design decisions

### Documentation Standards

- Use clear, concise language
- Include code examples where appropriate
- Provide step-by-step instructions
- Add screenshots for UI-related tasks
- Document prerequisites and dependencies

## Commit Guidelines

- Use descriptive commit messages
- Start with a verb (Add, Update, Fix, Remove)
- Keep the first line under 50 characters
- Add detailed description if needed

Example:
```
Add Docker containerization experiment

- Created Dockerfile for Node.js application
- Added docker-compose configuration
- Included setup instructions and troubleshooting guide
```

## Pull Request Process

1. **Update your branch** with the latest changes:
   ```bash
   git fetch upstream
   git rebase upstream/main
   ```

2. **Test your changes** thoroughly

3. **Create a pull request** with:
   - Clear title describing the change
   - Detailed description of what was added/changed
   - Any special instructions for testing

4. **Address feedback** from reviewers promptly

## Code of Conduct

- Be respectful and constructive in discussions
- Help fellow students with their experiments
- Share knowledge and learnings
- Follow academic integrity guidelines

## Need Help?

- Check existing issues and discussions
- Ask questions in the course forum
- Reach out to instructors or TAs
- Create an issue for bugs or suggestions

## Review Process

- All contributions are reviewed by instructors or TAs
- Feedback will be provided for improvements
- Once approved, changes will be merged to main branch

Happy learning and contributing! 🚀