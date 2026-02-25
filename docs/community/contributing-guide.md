# Community Contribution Guide

Detailed guide on how to contribute to the Vibe Coding project.

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
Before contributing to Vibe Coding, please ensure you have:
- A GitHub account
- Basic knowledge of Git and Markdown
- Understanding of the Vibe Coding philosophy and principles
- Experience with mindful, creative, or collaborative coding practices

### First Steps
1. **Fork the Repository**
   Click the "Fork" button at the top right of the Vibe Coding repository page

2. **Clone Your Fork**
   ```bash
   git clone https://github.com/YOUR_USERNAME/vibe-coding-skills.git
   cd vibe-coding-skills
   ```

3. **Create a Branch**
   ```bash
   git checkout -b vibe-enhancement/your-contribution-type
   ```

4. **Make Your Changes**
   Follow the contribution guidelines below

5. **Submit a Pull Request**
   Push your changes and create a pull request to the main repository

## Ways to Contribute

### 1. Adding New Vibe Skills
Add relevant skills that embody the Vibe Coding philosophy:

**Guidelines:**
- Ensure the skill aligns with Vibe Coding principles
- Include a clear, inspiring description
- Add relevant activities when possible
- Follow the existing format: `- [ ] Skill Name - Description`

**Example:**
```markdown
- [ ] Mindful Code Review Practice - Approaching code reviews with empathy and learning focus
```

### 2. Improving Existing Skills
Enhance existing skill descriptions or activities:

**Guidelines:**
- Make descriptions more inspiring and actionable
- Update outdated information
- Add or replace activities with better alternatives
- Fix grammatical or spelling errors

### 3. Translations
Help translate content to new languages:

**Guidelines:**
- Create `_zh.md` or `_es.md` versions of existing documents
- Maintain philosophical accuracy while ensuring cultural relevance
- Use consistent terminology across translated documents
- Preserve the inspirational tone of Vibe Coding

### 4. Documentation
Improve project documentation:

**Areas to focus on:**
- User guides and tutorials
- Philosophy explanations
- Activity descriptions
- Best practices documentation
- Community resources

### 5. Activities & Exercises
Create new activities that cultivate Vibe Coding skills:

**Guidelines:**
- Design activities that genuinely enhance joy and mindfulness
- Ensure activities are inclusive and accessible
- Include clear instructions and expected outcomes
- Consider different skill levels when designing activities

### 6. Code and Structure
Improve project structure and code:

**Examples:**
- Fix broken links in documentation
- Improve folder organization
- Add missing metadata to files
- Create utility scripts for content management

### 7. Bug Reports
Report issues with the project:

**Include in bug reports:**
- Clear description of the issue
- Steps to reproduce
- Expected vs. actual behavior
- Screenshots if applicable

### 8. Feature Requests
Propose new features or improvements:

**Good feature requests include:**
- Problem statement
- Proposed solution
- Benefits to the community
- Potential implementation approach

## Code of Conduct

By participating in this project, you agree to abide by our [Code of Conduct](../../CODE_OF_CONDUCT.md). Please read it before contributing. This project aims to foster a welcoming and positive community aligned with Vibe Coding principles.

### Expected Behavior
- Be respectful and inclusive
- Provide constructive feedback with empathy
- Show compassion towards other community members
- Respect diverse viewpoints and experiences
- Celebrate differences and unique perspectives

### Unacceptable Behavior
- Harassment or discrimination of any kind
- Inflammatory or offensive comments
- Personal attacks
- Publishing others' private information without consent
- Dismissive treatment of others' experiences or feelings

## Development Setup

### Required Tools
- Git
- Text editor or IDE
- Basic command-line tools
- Web browser for viewing Markdown files

### Project Structure
```
vibe-coding-skills/
├── README.md                 # Project overview
├── docs/                     # Documentation hub
│   ├── getting-started/      # Getting started guides
│   ├── vibe-coding-skills/   # Vibe coding specific content
│   └── community/            # Community resources
├── skill-lists/              # Vibe coding skill checklists by level
│   ├── beginner/             # Beginner vibe coder skills
│   ├── intermediate/         # Intermediate vibe coder skills
│   ├── advanced/             # Advanced vibe coder skills
│   └── expert/               # Expert vibe coder skills
├── resources/                # Vibe-focused resources
└── .github/                  # GitHub configuration
```

### Working with Markdown
Vibe Coding uses Markdown for all documentation and skill lists:

**Standard Format for Skill Lists:**
```markdown
# Category Title

- [ ] Vibe Skill Name - Inspirational description of the skill
- [ ] Another Vibe Skill - Another inspiring description
- [x] Completed Vibe Skill - This one is checked off indicating completion

## Activities & Exercises

1. [Activity Name](https://example.com) - Description of the vibe-building activity
2. [Another Activity](https://example.com) - Description of another activity
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
   - Ensure consistency with Vibe Coding philosophy
   - Confirm that content is inspiring and actionable

3. **Commit Your Changes**
   ```bash
   git add .
   git commit -m "Brief description of vibe-focused changes"
   git push origin your-branch
   ```

4. **Create Pull Request**
   - Go to the Vibe Coding repository on GitHub
   - Click "Compare & pull request"
   - Fill out the PR template
   - Submit for review

### Commit Message Guidelines
- Use present tense ("Add" not "Added")
- Keep messages concise but descriptive
- Prefix with area when helpful (e.g., "Docs: Add user guide", "Skills: Update beginner list")
- Emphasize the positive, vibe-enhancing aspect of changes

**Examples:**
```
✅ Add mindful breathing exercise to beginner skills
✅ Enhance joyful collaboration techniques in intermediate level
✅ Improve activities for creative coding exploration
```

### Pull Request Requirements
- Changes must be related to a single issue or improvement
- All content must align with Vibe Coding principles
- Links should be functional and appropriate
- Changes should add value to the community
- PR description should explain the positive impact of changes

## Documentation Standards

### Writing Style
- Use positive, inspiring language
- Write in active voice when possible
- Maintain consistent terminology
- Ensure philosophical alignment with Vibe Coding
- Use inclusive language that welcomes all experience levels

### Markdown Formatting
- Use proper heading hierarchy (# through ######)
- Use bullet points for lists (- for unordered lists)
- Format code with backticks (`code`)
- Link to external resources with proper attribution

### Content Quality
- Ensure accuracy while maintaining inspiration
- Keep content relevant to Vibe Coding philosophy
- Include practical, actionable information
- Provide context where necessary
- Maintain an uplifting tone throughout

## Review Process

### Initial Review
When you submit a pull request, it will undergo:
1. **Automated checks** (if implemented)
2. **Manual review** by project maintainers
3. **Community feedback** (encouraged)

### Review Criteria
Changes are evaluated based on:
- **Alignment**: Content fits Vibe Coding philosophy
- **Inspiration**: Writing motivates and uplifts readers
- **Actionability**: Information is practical and implementable
- **Value**: Contribution adds meaningful value to vibe development
- **Consistency**: Follows project standards and tone

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
- Provide constructive feedback with empathy
- Celebrate others' contributions

### Collaboration
- Build upon others' ideas
- Share knowledge generously
- Welcome newcomers with warmth
- Foster an inclusive and supportive environment

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
- **Vibe Supporter**: Individual contributions
- **Vibe Builder**: Multiple meaningful contributions
- **Vibe Leader**: Significant impact on project direction

## Getting Help

### When Stuck
If you need help with your contribution:
1. **Check existing documentation**
2. **Search past issues for similar problems**
3. **Ask in a new issue** if you can't find an answer

### Mentorship
- Experienced contributors are encouraged to mentor newcomers
- Join discussions and offer guidance
- Share resources for learning Vibe Coding

## Conclusion

Thank you for considering contributing to Vibe Coding! Your contributions help create a more joyful, mindful, and creative approach to software development. Every contribution, big or small, adds to the positive energy of our community.

Remember that contributing is a learning process. Don't hesitate to ask questions, and welcome feedback as an opportunity to grow. Together, we can create a vibrant and supportive resource for developers who value joy, creativity, and positive collaboration.

Happy contributing!