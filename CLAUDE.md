# Mintlify Documentation Monorepo

## Working relationship
- You can push back on ideas-this can lead to better documentation. Cite sources and explain your reasoning when you do so
- ALWAYS ask for clarification rather than making assumptions
- NEVER lie, guess, or make up information

## Monorepo Structure
This repository contains three separate Mintlify documentation projects:
- **`/pragma`**: Pragma Oracle documentation
- **`/0d-finance`**: 0D Finance documentation
- **`/glacier`**: Pragma Glacier data-as-a-service documentation

Each subdirectory has its own `docs.json`, content files, and assets. When working on documentation:
- Identify which documentation you're working on (Pragma or 0D Finance)
- Navigate to the appropriate subdirectory
- Each project has its own CLAUDE.md with project-specific instructions

## Project Context
- Format: MDX files with YAML frontmatter
- Config: docs.json for navigation, theme, settings (in each subdirectory)
- Components: Mintlify components

## Content Strategy
- Document just enough for user success - not too much, not too little
- Prioritize accuracy and usability of information
- Make content evergreen when possible
- Search for existing information before adding new content. Avoid duplication unless it is done for a strategic reason
- Check existing patterns for consistency
- Start by making the smallest reasonable changes

## docs.json
- Refer to the [docs.json schema](https://mintlify.com/docs.json) when building the docs.json file and site navigation
- Each project has its own docs.json in its subdirectory

## Frontmatter Requirements for Pages
- title: Clear, descriptive page title
- description: Concise summary for SEO/navigation

## Writing Standards
- Second-person voice ("you")
- Prerequisites at start of procedural content
- Test all code examples before publishing
- Match style and formatting of existing pages
- Include both basic and advanced use cases
- Language tags on all code blocks
- Alt text on all images
- Relative paths for internal links

## Git Workflow
- NEVER use --no-verify when committing
- Ask how to handle uncommitted changes before starting
- Create a new branch when no clear branch exists for changes
- Commit frequently throughout development
- NEVER skip or disable pre-commit hooks

## Do Not
- Skip frontmatter on any MDX file
- Use absolute URLs for internal links
- Include untested code examples
- Make assumptions - always ask for clarification
- Create files unless they're absolutely necessary for achieving your goal
- Skip or disable pre-commit hooks

## Important Reminders
- ALWAYS prefer editing an existing file to creating a new one
- NEVER proactively create documentation files (*.md) or README files unless explicitly requested
- Do what has been asked; nothing more, nothing less
