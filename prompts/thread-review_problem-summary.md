# Thread Review Prompt - Problem Summary
Version: 20260206

Please create a Problem Summary document for this thread following these guidelines:

## Document Structure
- **Title**: Use the topic header created for the thread
- **Format**: Markdown file (.md)
- **Filename**: Use the thread topic as the filename with "-problem-summary" appended
- **Audience**: Technical team members
- **Writing Style**: Use nominalize style (nominal/noun-based phrasing)

## Content Guidelines
- Use the user's posts to determine which details from assistant responses to include
- Include only the steps/details that the user actually executed or confirmed
- Exclude speculative approaches, abandoned methods, or steps made irrelevant by conversation flow
- If multiple steps were suggested but only the first was performed before the conversation changed direction, include only what was actually done

## Required Sections

### Problem Statement
- Date range of issue (first and last exchange dates)
- Clear description of the problem encountered
- Impact or symptoms observed
- Initial context or circumstances that led to the issue

### Investigation
- Actions taken to investigate the problem
- Commands executed with expected and actual results
- Ad hoc scripts used during troubleshooting with expected and actual results
- Applications or packages needed for troubleshooting
- Diagnostic findings and observations
- Use structured narrative format:
  - Action taken: [command/script/procedure]
  - Expected result: [what should have happened]
  - Actual result: [what actually happened]

### Resolution
- The fix implemented to resolve the problem
- Distinguish between permanent fix and workaround
- Configuration changes made
- Specific commands or procedures used for resolution
- Verification steps confirming the fix

### Unresolved Issues (if applicable)
- Problems related to the issue that remain unresolved
- Distinction between resolved and unresolved elements
- Omit this section if all problems were fully resolved

### Tools Used (if applicable)
- List only tools that needed to be installed or added during troubleshooting
- Include installation commands or procedures if relevant
- Omit this section if no new tools were required

### Additional Resources
- Links to relevant documentation
- References to related issues or tickets
- External resources consulted

### Related Articles
- Links to related KB articles or documentation
- Cross-references to similar issues
- Omit if this is a standalone issue

## Metadata
- **Last Updated**: [Date in YYYYMMDD format]
- **Version**: [YYYYMMDD.increment format for tracking changes]

OUTPUT AS ARTIFACT
