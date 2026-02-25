# Community Contribution Guide

Detailed guide on how to contribute to the Skills4Coder project.

## 🌐 Languages
- [English](contributing-guide.md) | [中文](contributing-guide_zh.md)

## Table of Contents
1. [Getting Started](#getting-started)
2. [Ways to Contribute](#ways-to-contribute)
3. [Code of Conduct](#code-of-conduct)
4. [Development Setup](#development-setup)
5. [Submitting Changes](#submitting-changes)
6. [Documentation Standards](#documentation-standards)
7. [Review Process](#review-process)
8. [Community Guidelines](#community-guidelines)

## Getting Started

### Prerequisites
Before contributing to Skills4Coder, please ensure you have:
- A GitHub account
- Basic knowledge of Git and Markdown
- Understanding of the skill level you wish to contribute to (Beginner, Intermediate, Advanced, Expert)

### First Steps
1. **Fork the Repository**
   Click the "Fork" button at the top right of the Skills4Coder repository page

2. **Clone Your Fork**
   ```bash
   git clone https://github.com/YOUR_USERNAME/skills4coder.git
   cd skills4coder
   ```

3. **Create a Branch**
   ```bash
   git checkout -b feature/your-contribution-type
   ```

4. **Make Your Changes**
   Follow the contribution guidelines below

5. **Submit a Pull Request**
   Push your changes and create a pull request to the main repository

## Ways to Contribute

### 1. Adding New Skills
Add relevant skills to existing or new skill lists:

**Guidelines:**
- Ensure the skill fits the target level's competency
- Include a clear, concise description
- Add relevant learning resources when possible
- Follow the existing format: `- [ ] Skill Name - Description`

**Example:**
```markdown
- [ ] Git Branching - Understanding how to create, merge, and manage branches in Git
```

### 2. Improving Existing Skills
Enhance existing skill descriptions or learning resources:

**Guidelines:**
- Make descriptions clearer and more accurate
- Update outdated information
- Add or replace learning resources with better alternatives
- Fix grammatical or spelling errors

### 3. Translations
Help translate content to new languages:

**Guidelines:**
- Create `_zh.md` or `_es.md` versions of existing documents
- Maintain technical accuracy while ensuring cultural relevance
- Use consistent terminology across translated documents
- Include language navigation where appropriate

### 4. Documentation
Improve project documentation:

**Areas to focus on:**
- User guides and tutorials
- FAQ sections
- Contribution guidelines
- Community resources
- Best practices documentation

### 5. Code and Structure
Improve project structure and code:

**Examples:**
- Fix broken links in documentation
- Improve folder organization
- Add missing metadata to files
- Create utility scripts for content management

### 6. Bug Reports
Report issues with the project:

**Include in bug reports:**
- Clear description of the issue
- Steps to reproduce
- Expected vs. actual behavior
- Screenshots if applicable

### 7. Feature Requests
Propose new features or improvements:

**Good feature requests include:**
- Problem statement
- Proposed solution
- Benefits to the community
- Potential implementation approach

## Code of Conduct

By participating in this project, you agree to abide by our [Code of Conduct](../../CODE_OF_CONDUCT.md). Please read it before contributing.

### Expected Behavior
- Be respectful and inclusive
- Provide constructive feedback
- Show empathy towards other community members
- Respect diverse viewpoints and experiences

### Unacceptable Behavior
- Harassment or discrimination of any kind
- Inflammatory or offensive comments
- Personal attacks
- Publishing others' private information without consent

## Development Setup

### Required Tools
- Git
- Text editor or IDE
- Basic command-line tools
- Web browser for viewing Markdown files

### Project Structure
```
skills4coder/
├── README.md                 # Project overview
├── docs/                     # Documentation hub
│   ├── getting-started/      # Getting started guides
│   ├── skill-lists-info/     # Skill lists information
│   └── community/            # Community resources
├── skill-lists/              # Skill checklists by level
│   ├── beginner/             # Beginner level skills
│   ├── intermediate/         # Intermediate level skills
│   ├── advanced/             # Advanced level skills
│   └── expert/               # Expert level skills
├── resources/                # Learning resources
└── .github/                  # GitHub configuration
```

### Working with Markdown
Skills4Coder uses Markdown for all documentation and skill lists:

**Standard Format for Skill Lists:**
```markdown
# Category Title

- [ ] Skill Name - Brief description of the skill
- [ ] Another Skill - Another brief description
- [x] Completed Skill - This one is checked off indicating completion

## Learning Resources

1. [Resource Name](https://example.com) - Description of the resource
2. [Another Resource](https://example.com) - Description of another resource
```

## Submitting Changes

### Pull Request Process
1. **Update Your Fork**
   ```bash
   git checkout main
   git pull upstream main
   git checkout your-branch
   git rebase main
   ```

2. **Verify Your Changes**
   - Test links and references
   - Check formatting and grammar
   - Ensure consistency with existing content

3. **Commit Your Changes**
   ```bash
   git add .
   git commit -m "Brief description of changes"
   git push origin your-branch
   ```

4. **Create Pull Request**
   - Go to the Skills4Coder repository on GitHub
   - Click "Compare & pull request"
   - Fill out the PR template
   - Submit for review

### Commit Message Guidelines
- Use present tense ("Add" not "Added")
- Keep messages concise but descriptive
- Prefix with area when helpful (e.g., "Docs: Add user guide", "Skills: Update beginner list")

**Examples:**
```
✅ Add new security skills to advanced level
✅ Fix typo in intermediate skill descriptions
✅ Update learning resources for API development
```

### Pull Request Requirements
- Changes must be related to a single issue or improvement
- All content must follow the project's style guidelines
- Links should be functional and appropriate
- Changes should add value to the community
- PR description should explain the changes made

## Documentation Standards

### Writing Style
- Use clear, concise language
- Write in active voice when possible
- Maintain consistent terminology
- Ensure technical accuracy

### Markdown Formatting
- Use proper heading hierarchy (# through ######)
- Use bullet points for lists (- for unordered lists)
- Format code with backticks (`code`)
- Link to external resources with proper attribution

### Content Quality
- Ensure factual accuracy
- Keep content relevant to the skill level
- Include practical, actionable information
- Provide context where necessary

## Review Process

### Initial Review
When you submit a pull request, it will undergo:
1. **Automated checks** (if implemented)
2. **Manual review** by project maintainers
3. **Community feedback** (encouraged)

### Review Criteria
Changes are evaluated based on:
- **Accuracy**: Information is factually correct
- **Relevance**: Content fits the target audience and level
- **Clarity**: Writing is clear and understandable
- **Value**: Contribution adds meaningful value
- **Consistency**: Follows project standards and format

### Addressing Feedback
- Respond promptly to review comments
- Make requested changes in a timely manner
- Ask for clarification if needed
- Thank reviewers for their input

### Approval Process
- At least one maintainer approval required
- Address all feedback before merging
- PR author should not approve their own PR

## Community Guidelines

### Communication
- Be patient and understanding
- Ask questions respectfully
- Provide constructive feedback
- Celebrate others' contributions

### Collaboration
- Build upon others' ideas
- Share knowledge generously
- Welcome newcomers
- Foster an inclusive environment

### Continuous Improvement
- Stay engaged with ongoing discussions
- Propose improvements thoughtfully
- Test your changes before submitting
- Learn from feedback and mistakes

## Recognition

### Contributor Credits
Contributors are acknowledged in:
- Pull request merge messages
- Project release notes
- Special contributor sections in documentation

### Contribution Levels
- **Community Contributor**: Individual contributions
- **Core Contributor**: Multiple significant contributions
- **Maintainer**: Ongoing project oversight and management

## Getting Help

### When Stuck
If you need help with your contribution:
1. **Check existing documentation**
2. **Search past issues for similar problems**
3. **Ask in a new issue** if you can't find an answer

### Mentorship
- Experienced contributors are encouraged to mentor newcomers
- Join discussions and offer guidance
- Share resources for learning

## Conclusion

Thank you for considering contributing to Skills4Coder! Your contributions help make this project valuable for developers worldwide. Every contribution, big or small, is appreciated and makes a difference.

Remember that contributing is a learning process. Don't hesitate to ask questions, and welcome feedback as an opportunity to improve. Together, we can create a comprehensive and helpful resource for developers at all levels.

Happy contributing!