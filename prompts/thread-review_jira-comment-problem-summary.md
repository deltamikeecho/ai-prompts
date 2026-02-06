# Thread Review Prompt – Problem Summary to Jira Comment
Version: 20260206.1

## Purpose
Provide a repeatable, Jira-friendly way to publish a Problem Summary *inside the Story as a comment*, avoiding attachments and preserving readable formatting.

## Where to Put the Content
- Paste the Problem Summary as a **single comment** on the Jira Story immediately after creation.
- Keep the Story **Description** high-level (issue, dates, outcome). Put detailed investigation/resolution in the **comment**.

## Renderer Guidance
- Preferred: **Jira Wiki Renderer** (Cloud & Server/DC).
- If your project uses Markdown, the same comment renders correctly (headings, lists, `{code}` blocks).

## Structure to Use (Jira Comment)
1. **Header**
   - Title: *Problem Summary — <System/Topic>*
   - Date range, Service/Area, Impact (one–two lines each)

2. **Context**
   - Brief environment and change window information (one paragraph)

3. **Tools Needed (non‑default) — *MANDATORY if any tools were installed***
   - Explicitly **list tools that are not part of the standard environment** but were required for troubleshooting (e.g., installing a **JDK** to obtain **`keytool`**).
   - Include the exact package/command used to install them, for reproducibility.
   - Example:
     ```text
     dnf install -y java-11-openjdk-devel   # required to use keytool to inspect Java truststore
     ```

4. **Investigation**
   - Bullet steps with brief narrative.
   - For commands and outputs, wrap in `{code}` blocks.
   - Use *Expected* vs *Actual* when helpful.

5. **Resolution**
   - Bullet list of final corrective actions.
   - Include verification steps and final pass criteria (e.g., UI test success, fingerprints matched).

6. **Notes / Gotchas**
   - Environment constraints, common pitfalls (e.g., trustStore overrides, load-balancer hostname issues).

## Example Snippets

### Header