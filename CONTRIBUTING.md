# Contributing to Nebulai Agent Space

Thank you for your interest in contributing to Agent Space! We're excited to have you join our mission to build the future of decentralized AI infrastructure. This guide will help you get started with contributing to our project.

## 🚀 Quick Start

1. **Fork the repository** on GitHub
2. **Clone your fork** locally:
   ```bash
   git clone https://github.com/YOUR_USERNAME/AgentSpace.git
   cd AgentSpace
   ```
3. **Add upstream remote**:
   ```bash
   git remote add upstream https://github.com/NebulaiNetwork/AgentSpace.git
   ```
4. **Create a feature branch**:
   ```bash
   git checkout -b feature/your-feature-name
   ```

## 📋 Contribution Guidelines

### Before You Start

- Check existing [issues](https://github.com/NebulaiNetwork/AgentSpace/issues) and [pull requests](https://github.com/NebulaiNetwork/AgentSpace/pulls) to avoid duplicates
- Join our [Discord](https://discord.gg/kyVHRQSFyg) and [Telegram](https://t.me/Nebulai_HQ) communities
- Read our [documentation](https://docs.nebulai.network) to understand the architecture

### What Can You Contribute?

We welcome various types of contributions:

#### 🔧 Code Contributions
- Bug fixes and improvements
- New agent implementations
- Performance optimizations
- Test coverage improvements

#### 📚 Documentation
- README improvements
- API documentation
- Architecture diagrams
- Tutorial creation
- Translation to other languages

#### 🎨 Design & UX
- UI/UX improvements
- Diagrams and visualizations
- Better error messages

#### 🧪 Testing
- Unit tests
- Integration tests
- Performance benchmarks
- Bug reports with reproducible steps

### Agent Registration Guidelines

When contributing a new agent:

1. **Carefully design your agent's functionality** before registration
2. **Choose appropriate tags** that accurately represent the agent's capabilities
3. **Follow this JSON format**:
   ```json
   {
     "url": "https://your-agent-endpoint.com",
     "name": "Descriptive Agent Name",
     "tag": [1, 3, 4],
     "description": "Clear description of what your agent does",
     "author": "Your GitHub username",
     "version": "1.0.0"
   }
   ```
4. **Test thoroughly** - poorly performing agents affect overall system ratings
5. **Document your agent's**:
   - Input/output formats
   - Required parameters
   - Rate limits
   - Example usage

## 🔄 Development Workflow

### 1. Keep Your Fork Updated

```bash
git fetch upstream
git checkout main
git merge upstream/main
```

### 2. Make Your Changes

- Write clean, readable code
- Follow existing code style
- Add comments for complex logic
- Update tests if applicable
- Update documentation

### 3. Commit Guidelines

We follow [Conventional Commits](https://www.conventionalcommits.org/):

- `feat:` New feature
- `fix:` Bug fix
- `docs:` Documentation changes
- `style:` Code style changes (formatting, etc.)
- `refactor:` Code refactoring
- `test:` Adding or updating tests
- `chore:` Maintenance tasks

Example:
```bash
git commit -m "feat: add validation for agent registration"
```

### 4. Push and Create Pull Request

```bash
git push origin feature/your-feature-name
```

Then create a PR on GitHub with:
- Clear title following commit conventions
- Detailed description of changes
- Reference any related issues
- Screenshots/demos if applicable

## 🐛 Reporting Issues

When reporting issues, please include:

1. **Clear title** describing the problem
2. **Environment details**:
   - OS and version
   - Node.js/Python version
   - Agent Space version
3. **Steps to reproduce**
4. **Expected behavior**
5. **Actual behavior**
6. **Error messages/logs**
7. **Screenshots** if applicable

## 💡 Proposing Features

1. Check if the feature has already been proposed
2. Open an issue with `[Feature Request]` prefix
3. Describe:
   - The problem it solves
   - Proposed solution
   - Alternative solutions considered
   - Impact on existing features

## 🏆 Recognition

We value all contributions! Contributors will be:
- Listed in our CONTRIBUTORS.md file
- Eligible for Nebulai ecosystem rewards
- Invited to exclusive contributor events
- Given priority access to new features

## 📊 Code Standards

### General Guidelines
- Keep functions small and focused
- Use descriptive variable names
- Avoid deep nesting (max 3 levels)
- Handle errors gracefully
- Log important operations

### Python Code Style
- Follow [PEP 8](https://pep8.org/)
- Use type hints where applicable
- Docstrings for all public functions

### JavaScript/TypeScript
- Use ES6+ features
- Semicolons required
- 2 spaces for indentation
- Use `const` and `let`, avoid `var`

## 🚦 Review Process

1. **Automated checks** run on all PRs
2. **Maintainer review** for code quality and alignment
3. **Community feedback** period (48 hours)
4. **Merge** after approval

**Review criteria:**
- Code quality and style
- Test coverage
- Documentation updates
- Performance impact
- Security considerations

## 🔐 Security

- Never commit sensitive data
- Report security issues privately to security@nebulai.network
- Follow secure coding practices
- Validate all inputs
- Use environment variables for configuration

## 🤝 Community

- Be respectful and inclusive
- Help others in discussions
- Share knowledge and learnings
- Celebrate others' contributions

## 📬 Getting Help

- **Discord**: [Join our server](https://discord.gg/kyVHRQSFyg)
- **Telegram**: [@Nebulai_HQ](https://t.me/Nebulai_HQ)
- **Documentation**: [docs.nebulai.network](https://docs.nebulai.network)
- **Issues**: Use GitHub issues for bugs and features

## License

By contributing, you agree that your contributions will be licensed under the same license as the project (check LICENSE file).

---

Thank you for contributing to the decentralized AI future! 🚀
