# Agentic Copilot Development Exercise

A structured workspace for developing AI-assisted applications using GitHub Copilot with custom instructions and prompts.

## 📁 Project Structure

```
.
├── .github/
│   ├── copilot-instructions.md    # Custom GitHub Copilot instructions
│   └── prompts/
│       ├── implement.prompt.md    # Implementation guidance prompts
│       └── spec.prompt.md         # Specification generation prompts
├── .vscode/
│   └── settings.json             # VS Code configuration
├── code/                         # Source code directory
├── project/
│   ├── proposal.md              # Project proposal document
│   └── specs/                   # Technical specifications
├── .gitignore                   # Git ignore rules
└── README.md                    # This file
```

## 🚀 Getting Started

### Prerequisites

- Visual Studio Code
- GitHub Copilot extension
- Git

### Setup

1. Clone this repository:
   ```powershell
   git clone <repository-url>
   cd agentic-copilot-day-ex1
   ```

2. Open in Visual Studio Code:
   ```powershell
   code .
   ```

3. The workspace is pre-configured with custom Copilot instructions that will automatically be loaded.

## 🤖 GitHub Copilot Configuration

This project includes custom GitHub Copilot instructions that emphasize:

- **Code Quality**: Prioritizing readability, clarity, and maintainability
- **Algorithm Documentation**: Including explanations of approaches used
- **Edge Case Handling**: Comprehensive error handling and input validation
- **Testing**: Built-in test case generation for critical paths
- **Windows Environment**: Commands formatted for Windows command line/PowerShell

### Custom Instructions Features

- Automatic use of instruction files (configured in `.vscode/settings.json`)
- Structured prompts for specification generation
- Implementation guidance with step-by-step approach
- Documentation requirements for all code

## 📋 Development Workflow

### 1. Proposal Phase
- Document high-level project requirements in [`project/proposal.md`](project/proposal.md)

### 2. Specification Phase
- Use the [spec prompt](.github/prompts/spec.prompt.md) to generate detailed technical specifications
- Store specifications in the `project/specs/` directory

### 3. Implementation Phase
- Use the [implementation prompt](.github/prompts/implement.prompt.md) to create step-by-step implementation plans
- Develop code in the `code/` directory following the established guidelines

## 🛠️ Code Standards

All code generated follows these principles:
- **Readability**: Clear, understandable code structure
- **Maintainability**: Well-commented with design decision explanations
- **Robustness**: Comprehensive edge case and error handling
- **Testing**: Unit tests and acceptance criteria included
- **Documentation**: Complete file and function-level documentation

## 📝 Documentation Requirements

- File-level documentation explaining purpose and scope
- Component/function-level documentation with inputs/outputs
- Inline comments for complex logic
- Type documentation for interfaces
- Edge case and error handling notes
- Assumptions and limitations documented

## 🧪 Testing Strategy

The project emphasizes comprehensive testing:
- **Unit Tests**: For business logic validation
- **Edge Cases**: Empty inputs, invalid data types, large datasets
- **Acceptance Tests**: UI-level test steps for requirements fulfillment
- **Error Scenarios**: API failures, validation errors, etc.

## 📚 Resources

- [GitHub Copilot Instructions](.github/copilot-instructions.md)
- [Specification Prompt](.github/prompts/spec.prompt.md)
- [Implementation Prompt](.github/prompts/implement.prompt.md)

## Attributions
Various templates borrowed from my esteemed colleagues:
- [pamelafox/awesome-copilot-instructions](https://github.com/pamelafox/awesome-copilot-instructions)
- [pierceboggan/vibe-coding-template](https://github.com/pierceboggan/vibe-coding-template)