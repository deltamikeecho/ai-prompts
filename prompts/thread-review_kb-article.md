# Thread Review Prompt - KB Article
Version: 20260206

Please create a KB Article document for this thread following these guidelines:

## Document Structure
- **Title**: Use the topic header created for the thread
- **Format**: Markdown file (.md)
- **Filename**: Use the thread topic as the filename with "-kb-article" appended
- **Audience**: Technical team members
- **Writing Style**: Use nominalize style (nominal/noun-based phrasing)

## Content Guidelines
- Use the user's posts to determine which details from assistant responses to include
- Include only the steps/details that the user actually executed or confirmed
- Exclude speculative approaches, abandoned methods, or steps made irrelevant by conversation flow
- If multiple steps were suggested but only the first was performed before the conversation changed direction, include only what was actually done
- Focus on established solutions and best practices

## Required Sections

### Problem
- Clear description of the issue or scenario this article addresses
- Symptoms or indicators that help identify when this solution applies
- Context or circumstances when this problem typically occurs

### Solution
- Step-by-step resolution procedure
- Commands to execute with expected output
- Configuration changes needed
- Verification steps to confirm success
- If troubleshooting steps are involved:
  - Include specific commands or ad hoc scripts used
  - Document expected output for each step
  - Note applications or packages needed for troubleshooting

### Tools Used (if applicable)
- List only tools that needed to be installed or added
- Include installation commands or procedures if relevant
- Omit this section if no new tools were required

### Additional Resources
- Links to relevant documentation
- References to related systems or configuration files
- External resources or official documentation
- Omit if no additional resources are applicable

### Related Articles
- Links to related KB articles
- Cross-references to similar issues or procedures
- Omit if this is a standalone article

## Metadata
- **Last Updated**: [Date in YYYYMMDD format]
- **Version**: [YYYYMMDD.increment format for tracking changes]

OUTPUT AS ARTIFACT
