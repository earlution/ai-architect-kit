# Version: MAJOR.MINOR.PATCH
**version** = "0.1.1"
updated 02.01.2025

# AI Architect Kit
A professional framework for architects and engineers working with AI programming assistants.

## Overview
AI Architect Kit provides a structured approach for software architects and engineers to effectively collaborate with AI programming assistants. It emphasizes clean architecture, atomic design principles, and proven patterns for maintaining software quality while leveraging AI capabilities.

## Core Principles
- **You are the Architect**: AI is your implementation partner, you make the design decisions
- **Clean Architecture**: Clear separation of concerns and component boundaries
- **Atomic Design**: Each component has a single, well-defined responsibility
- **Quality First**: Strong emphasis on testing, documentation, and maintainable code

## Additional Architectural Guidance

### Single Responsibility Principle (SRP)
**Rationale**: 
- Ensures each component, function, and module has a singular, well-defined purpose
- Improves code maintainability and testability
- Facilitates easier understanding and modification
- Reduces complexity and potential for unintended side effects

**Implementation Requirements**:
- Every component must have a clear, singular responsibility
- Components should be designed to do one thing and do it well
- Refactor immediately if a component starts to have multiple responsibilities

### Docs-as-Code Approach
**Rationale**:
- Treats documentation with the same rigour as code
- Enables version control for documentation
- Allows collaborative editing and review of documentation
- Ensures documentation stays in sync with code changes
- Facilitates easier maintenance and updates

**Implementation Requirements**:
- Store documentation in version control alongside code
- Use markdown or similar lightweight markup languages
- Leverage pull request and review processes for documentation changes
- Automate documentation generation where possible
- Documentation file structure mirrors implementation file structure

### Changelog Management
**Rationale**:
- Provides transparent project history
- Helps track feature additions, bug fixes, and changes
- Improves communication with project stakeholders
- Facilitates easier understanding of project evolution

**Implementation**: 
- Use 'keep-a-changelog' standard
- Automatically generate and update changelogs
- Ensure commit messages align with changelog entries

## Recommended Workflow

### Issue-Driven Development Workflow
1. **Test Preparation**
   - Create or update relevant test files
   - Ensure tests cover expected functionality and edge cases

2. **Implementation**
   - Develop code to pass prepared tests
   - Adhere to Single Responsibility Principle

3. **Testing**
   - Run comprehensive test suite
   - If tests fail:
     * Debug and modify implementation
     * Rerun tests until all pass
   - If tests pass, proceed to next step

4. **Changelog Generation**
   - Update CHANGELOG.md with detailed, clear entry
   - Describe changes, rationale, and impact

5. **Commit Process**
   - Stage relevant files
   - Create commit with message matching changelog entry
   - Ensure commit provides clear, concise description of changes

## Key Features
### 1. Project Structure
- Pre-configured atomic component layout
- Clear separation of concerns
- Documentation templates
- Testing infrastructure

### 2. Development Standards
- Comprehensive coding conventions
- Testing requirements
- Documentation standards
- Version control practices

### 3. AI Collaboration
- Guidelines for effective AI interaction
- Request templates
- Response validation frameworks
- Quality control checklists

### 4. Workflow Templates
- Issue templates
- Pull request templates
- Architecture Decision Records (ADRs)
- Changelog standards

## Getting Started
1. Click "Use this template" to create your new repository
2. Follow the [First Steps Guide](docs/getting-started.md)
3. Review the [AI Collaboration Guidelines](docs/ai-collaboration.md)
4. Start with the [Project Structure Documentation](docs/project-structure.md)

## Documentation
This repository includes comprehensive documentation on:
- [Architectural Principles](docs/architecture.md)
- [Development Workflow](docs/workflow.md)
- [Testing Strategy](docs/testing.md)
- [AI Collaboration Best Practices](docs/ai-collaboration.md)

## Learning Resources
- [Blog Series: Building with AI Assistance](https://www.soneaca.uk/tech/addressing-technical-debt-with-ai-assistance/)
- [Common Patterns and Anti-patterns](docs/patterns.md)
- [Case Studies](docs/case-studies.md)

## Contributing
We welcome contributions! Please see our [Contributing Guide](.github/CONTRIBUTING.md) for details.

## License
This project is licensed under the MIT Licence - see the [LICENSE](LICENSE) file for details.
