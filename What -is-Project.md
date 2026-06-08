
**Key takeaways**
- **Projects** are self-contained workspaces with their own memory, chat history, knowledge base, and instructions — a dedicated environment for a specific workstream.
- **Upload once:** project knowledge is available to all chats inside the project, so you don't need to re-upload the same files.
- **Project instructions** set Claude's global behavior for that project (tone, process, templates) and apply to every conversation.
- **Automatic scaling (RAG):** when content approaches context limits, Retrieval Augmented Generation (RAG) searches only the relevant pieces of your uploads, expanding capacity by up to **10x**.
- **Team sharing:** Projects can be shared with permission levels: **Can view**, **Can edit**, or **Owner**.

**What is a Project?**
Projects are focused workspaces that keep related knowledge, conversations, and rules in one place. Use a project whenever you want Claude to retain context across multiple chats or when several people need to work from the same background information.

**When to create a Project**
- Ongoing work or multi-step workflows (product launches, client accounts, research programs).
- Reused reference materials (brand guides, meeting notes, specs).
- Consistent response rules (always cite sources, use a formal template, follow a style guide).
- Collaboration where teammates should share the same context and instructions.

**Setting up your first project (quick)**
1. Open Projects and click **+ New Project**. Give it a clear name and short description.
2. Set visibility: **private** or **shared** with your organization.
3. Add **Project Instructions** — describe goals, tone, required steps, and any templates.
4. Upload key files to the knowledge base or connect Google Drive.

**Project instructions: write them like a recipe**
- **Purpose + audience:** "This project drafts B2B marketing content for Product X."
- **Process:** "First propose a structure, then draft, then add CTA and alt headline."
- **Tone & constraints:** "Professional, concise, avoid jargon, include one data-backed claim per section."

**Building the knowledge base**
- Upload **PDFs, DOCX, CSV, TXT, HTML**, or link drives.
- Use **descriptive filenames** — they improve retrieval (e.g., Q4-2025-Sales-Report.pdf).
- Upload **example outputs** you want Claude to emulate (good + bad samples help steer results).

**Scaling with RAG**
When content exceeds the chat context window, Claude enables **RAG**: it indexes your uploads and fetches only the most relevant excerpts for each request. The UI shows when RAG is active — the experience stays conversational, but capacity increases significantly.

**Collaboration & permissions**
- **Can view:** read and chat with project context but cannot edit.
- **Can edit:** modify instructions, add files, manage members.
- **Owner:** full control, invite or change permissions for others.

**Best practices & important additions**
- **Keep the KB current:** stale files lead to stale answers.
- **Onboarding note:** add a short guide in the project for new members (scope, norms, contacts).
- **Privacy & permissions:** do not upload sensitive personal data unless access controls meet your policy.
- **Versioning:** include dates or version numbers in filenames (e.g., v1.2, 2025-09-01).
- **Templates:** store briefs, summary templates, and email copy so Claude can reuse them consistently.

> **Pro tip:** Name files clearly and include one example output per major doc type — it makes Claude's outputs much more aligned.

**Quick checklist (ready-to-go)**
- Name & describe the project.
- Add clear project instructions.
- Upload 3–10 core documents with descriptive names.
- Add one template and one example output.
- Invite collaborators and set permissions.

**Examples of useful projects**
- **Q4 product launch:** specs, competitive research, messaging.
- **Client hub:** brand kit, past deliverables, communications history.
- **Research support:** interviews, synthesis notes, comparative analyses.

**Want changes?**
If you prefer a shorter executive summary, a slide-ready version, or onboarding copy for new members, tell me which format and I’ll produce it.

