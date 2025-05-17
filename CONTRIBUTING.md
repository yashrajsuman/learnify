# Contributing to Learnify

First off, thank you for considering contributing to Learnify! It's people like you that make Learnify such a great tool.

## Code of Conduct

This project and everyone participating in it is governed by our [Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code.

## How Can I Contribute?

### Reporting Bugs

Before creating bug reports, please check the issue list as you might find out that you don't need to create one. When you are creating a bug report, please include as many details as possible:

* Use a clear and descriptive title
* Describe the exact steps which reproduce the problem
* Provide specific examples to demonstrate the steps
* Describe the behavior you observed after following the steps
* Explain which behavior you expected to see instead and why
* Include screenshots and animated GIFs if possible

### Suggesting Enhancements

Enhancement suggestions are tracked as GitHub issues. When creating an enhancement suggestion, please include:

* Use a clear and descriptive title
* Provide a step-by-step description of the suggested enhancement
* Provide specific examples to demonstrate the steps
* Describe the current behavior and explain which behavior you expected to see instead
* Explain why this enhancement would be useful

### Pull Requests

* Fill in the required template
* Do not include issue numbers in the PR title
* Include screenshots and animated GIFs in your pull request whenever possible
* Follow our [coding standards](#coding-standards)
* End all files with a newline

## Development Process

1. Fork the repo and create your branch from `main`
2. If you've added code that should be tested, add tests
3. If you've changed APIs, update the documentation
4. Ensure the test suite passes
5. Make sure your code lints
6. Issue that pull request!

## Coding Standards

### TypeScript

* Use TypeScript for all new code
* Define interfaces for props and state
* Use proper type annotations
* Avoid using `any`

### React

* Use functional components with hooks
* Keep components small and focused
* Use proper prop types
* Follow React best practices

### Styling

* Use Tailwind CSS for styling
* Follow the existing component structure
* Use the shadcn/ui component system
* Maintain dark mode compatibility

### Git Commit Messages

* Use the present tense ("Add feature" not "Added feature")
* Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
* Limit the first line to 72 characters or less
* Reference issues and pull requests liberally after the first line

## Project Structure

When adding new features, please follow our project structure:

```
src/
├── components/     # Reusable UI components
├── pages/         # Page components
├── services/      # API and service integrations
├── store/         # State management
├── types/         # TypeScript type definitions
├── utils/         # Utility functions
└── lib/           # Shared libraries and configurations
```

## Testing

* Write tests for new features
* Update tests when modifying existing features
* Ensure all tests pass before submitting PR

## Documentation

* Update README.md with details of changes to the interface
* Update API documentation for any modified endpoints
* Add JSDoc comments for new functions and components

## Questions?

Don't hesitate to ask questions about the contribution process. We'll be happy to help!

## License

By contributing to Learnify, you agree that your contributions will be licensed under its MIT license.
