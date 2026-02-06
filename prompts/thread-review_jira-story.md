# Thread Review Prompt - Jira Story
Version: 20260206

Please create a Jira Story document for this thread following these guidelines:

## Document Structure
- **Title**: Use the topic header created for the thread
- **Format**: Markdown file (.md)
- **Filename**: Use the thread topic as the filename with "-jira-story" appended

## Content Guidelines
- Use the user's posts to determine which details from assistant responses to include
- Include only the steps/details that the user actually executed or confirmed
- Exclude speculative approaches, abandoned methods, or steps made irrelevant by conversation flow
- If multiple steps were suggested but only the first was performed before the conversation changed direction, include only what was actually done
- Use casual, conversational language rather than formal Agile terminology

## Required Sections

### Summary
- Brief one-line description of the work
- Should be concise enough to use as the Jira story title

### Description
- Date range of work (first and last exchange dates)
- The issue being addressed
- The cause of the issue if known upfront
- If investigation was needed: state that investigation needs to occur to determine the cause and fix
- If cause was already known: state that a specific fix needs to be implemented
- Keep tone casual and straightforward

### Acceptance Criteria
- Clear, testable criteria that define when the work is complete
- What needs to be working or in place for the story to be considered done
- Expected behavior or outcomes after implementation

### Story Comments (To be added after story creation)
- Document the steps taken to resolve the issue in chronological order
- Include commands executed, configurations changed, or procedures followed
- Capture key findings during implementation
- Note any adjustments made during the work
- These should be formatted as separate comments to maintain the flow of how stories are normally captured in Jira

## Metadata
- **Last Updated**: [Date in YYYYMMDD format]
- **Version**: [YYYYMMDD.increment format for tracking changes]

## Note
This story captures work that has already been completed. A Problem Summary document may be attached to provide additional troubleshooting details and investigation steps.

OUTPUT AS ARTIFACT
