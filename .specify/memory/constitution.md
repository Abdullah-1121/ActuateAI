<!--
Sync Impact Report:
Version change: None -> 1.0.0
List of modified principles: All principles added/defined
Added sections: Technical Stack, Development Workflow
Removed sections: None
Templates requiring updates:
- .specify/templates/plan-template.md: ⚠ pending
- .specify/templates/spec-template.md: ⚠ pending
- .specify/templates/tasks-template.md: ⚠ pending
- .specify/templates/commands/*.md: ⚠ pending
Follow-up TODOs: None
-->
# Physical AI & Humanoid Robotics Textbook Project Constitution

## Core Principles

### I. Test-Driven Development (TDD)
Every service and feature implementation MUST be guided by Test-Driven Development. Tests MUST be written and approved before any production code is implemented. The Red-Green-Refactor cycle is strictly enforced to ensure quality and maintainability.

### II. Best Practices for Software Development
All code MUST adhere to established software development best practices, including but not limited to: clean code principles, modularity, readability, maintainability, and scalability. Code reviews are mandatory for all changes.

### III. Documentation-First Approach
Comprehensive documentation is essential. This includes in-code comments for complex logic, clear READMEs for repositories, and detailed guides for setup and usage. The project's primary output is a Docusaurus-based textbook, which itself serves as core documentation.

### IV. Incremental and Iterative Development
Features will be developed using an agile approach, favoring small, incremental changes and frequent iterations. This allows for continuous feedback, early detection of issues, and adaptability to evolving requirements.

### V. Code Reference and Traceability
All code changes and discussions MUST include explicit code references (e.g., `file_path:line_number`) to ensure traceability and easy navigation within the codebase.

## Technical Stack

### I. Book Publishing
- **Framework**: Docusaurus (for static site generation and book structure)
- **Deployment**: GitHub Pages (for hosting the published textbook)

### II. RAG Chatbot Development
- **SDKs**: OpenAI Agents/ChatKit SDKs (for chatbot intelligence)
- **Backend Framework**: FastAPI (for API endpoints and chatbot logic)
- **Database**: Neon Serverless Postgres (for structured data storage)
- **Vector Database**: Qdrant Cloud Free Tier (for semantic search and retrieval in RAG)

### III. Development Tools
- **CLI**: Claude Code (for AI-native development and project management)
- **Specification**: Spec-Kit Plus (for spec-driven development)
- **Documentation**: context7 MCP server (for retrieving up-to-date library documentation)

## Development Workflow

### I. Feature Specification
All new features or significant changes MUST begin with a clear, concise specification using Spec-Kit Plus. The specification will define requirements, user scenarios, and success criteria before implementation begins.

### II. Code Review
All code changes MUST undergo a peer code review process. Reviewers will verify adherence to core principles, technical stack guidelines, and overall code quality.

### III. Automated Testing and CI/CD
Automated tests (unit, integration, end-to-end) are mandatory for all components. A continuous integration/continuous deployment (CI/CD) pipeline will ensure that all code is tested and deployed efficiently.

## Governance
This Constitution outlines the foundational principles and guidelines for the Physical AI & Humanoid Robotics Textbook Project. It supersedes all other informal practices. Amendments to this Constitution require a documented proposal, team approval, and a clear migration plan for any impacted practices or codebases. All pull requests and code reviews MUST verify compliance with these principles.

**Version**: 1.0.0 | **Ratified**: 2025-12-16 | **Last Amended**: 2025-12-16
