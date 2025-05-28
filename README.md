# Windsurf Project Template

This is a template repository for quickly starting new projects with Windsurf AI assistance configured. It includes AI workflow rules and configuration files to ensure consistent AI guidance across all your projects.

## What's Included

- `.cascade.json`: Configuration file for Windsurf AI assistant
- `AI_GUIDANCE.md`: General guidance for AI assistants
- `/rules`: Directory containing workflow rules for AI-assisted development
  - `create-prd.mdc`: For creating Product Requirement Documents
  - `generate-tasks.mdc`: For breaking down PRDs into actionable tasks
  - `process-task-list.mdc`: For implementing tasks one by one

## How to Use This Template

### Creating a New Project

1. Clone this template repository:
   ```bash
   git clone https://github.com/your-username/windsurf-template.git your-new-project
   ```

2. Navigate to your new project:
   ```bash
   cd your-new-project
   ```

3. Remove the existing git history and initialize a new repository:
   ```bash
   rm -rf .git
   git init
   ```

4. Update the project name and description in `.cascade.json`

5. Start building your project with AI assistance!

### Using AI Workflow Rules

Once your project is set up, you can use the included workflow rules:

1. **Start a feature with a PRD**:
   ```
   Use @rules/create-prd.mdc
   ```

2. **Generate a task list from your PRD**:
   ```
   Use @rules/generate-tasks.mdc
   ```

3. **Implement tasks one by one**:
   ```
   Use @rules/process-task-list.mdc
   ```

## Customizing the Template

Feel free to customize this template to fit your specific needs:

- Update `AI_GUIDANCE.md` with project-specific guidance
- Modify the rules in the `/rules` directory
- Add additional configuration to `.cascade.json`

## Creating a GitHub Template

To make this a proper GitHub template repository:

1. Push this to GitHub
2. Go to the repository settings
3. Check the "Template repository" option

This will allow you to create new repositories directly from this template via the GitHub interface.
