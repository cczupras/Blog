### Blog Post Generation from Notion

**Objective:** Read a source Notion page, synthesize the content, and create a blog post in a target Notion page under a specific section.

**Instructions:**

1.  **Read Notion Page:** Access my Notion database and read the content of the page titled `[Source Notion Page Title]`.
2.  **Synthesize Content:** Analyze the content, identify the main points, and draft a blog post in my personal writing style (Christian Blogger persona).
3.  **Target Location:**
    *   **Page:** `[Target Notion Page Title]`
    *   **Section:** `[Target Section Heading]`
4.  **Action:**
    *   If the target page exists, insert the generated blog post under the specified section.
    *   If you encounter issues updating the existing page, create a *new page* in the "Draft Blogs" database with the title `[New Draft Page Title]` and paste the content there.

**Tools:**
- use the notion mcp server to interact
- use `notion-update-page` to insert content into existing pages
- use `notion-create-page`to create a new page in notion

**Example Request:**

"Hey buddy, read the new page 'Cloning Workflows' in my Notion notes database and create a blog article for the '#2 Tech' section in the page '2025w37 - Clone'."
