# Assignment — Scenario to Shared Knowledge

## Outcome

You will turn one assigned troubleshooting scenario into a reusable Knowledge Article, publish it as a proposed GitHub change, review a peer's article, revise your work, and identify the accepted version.

> **Use this repository for this mission:** `student-operated-technology-ecosystem/CIT-205-classroom`
>
> Do **not** open the pull request against `SOTE-framework`. That repository is the protected operational framework. The classroom repository is the safe contribution layer designed for CIT-205.

## Phase 1 — Word Draft

1. Write clarification questions for **all six assigned scenarios**.
2. Participate in the class discussion.
3. Choose one scenario as directed by the instructor.
4. Copy the headings from the [Knowledge Article template](../templates/CLASSROOM-KA-TEMPLATE.md) into Word.
5. Write the article and submit the Word document through the instructor-designated course channel.

The Word file is your draft and course submission. Do not upload the `.docx` as the GitHub article.

## Phase 2 — Prepare Markdown

After instructor feedback, revise your draft. Copy the revised content into the Markdown template. Remove all names, student information, account details, credentials, and internal/private data.

Use this filename:

`KA-[your-GitHub-username]-[short-topic].md`

Example: `KA-jrivera-no-network.md`

## Phase 3 — Fork, Branch, and Propose

### A. Confirm the repository

Open the [CIT-205 Classroom repository](https://github.com/student-operated-technology-ecosystem/CIT-205-classroom).

Before continuing, confirm the page says:

`student-operated-technology-ecosystem / CIT-205-classroom`

and shows **Public**. You do not need SOTE organization membership or collaborator access.

### B. Fork

1. Select **Fork**.
2. Create your personal fork.
3. After GitHub opens the fork, confirm that **your GitHub username** appears as the repository owner and that the page identifies the repository as forked from `student-operated-technology-ecosystem/CIT-205-classroom`.

Your fork is your safe personal workspace.

### C. Create your branch

1. Open the branch selector.
2. Create a branch named `article/[your-GitHub-username]-[topic]`.
3. Confirm that the branch selector now shows your new branch before editing anything.

Example: `article/jrivera-no-network`

### D. Add the article

1. Open `knowledge/student-articles/`.
2. Choose **Add file → Create new file**.
3. Enter your required `KA-...md` filename.
4. Paste your revised Markdown article.
5. Use **Preview** to check the rendered headings, lists, spacing, and formatting.
6. Commit the file **to your article branch**, not `main`.

Suggested commit message: `Add no-network knowledge article draft`.

### E. Open the pull request

1. Choose **Contribute → Open pull request**, or use GitHub's **Compare & pull request** prompt.
2. On **Comparing changes**, verify the two sides before continuing:
   - **base repository:** `student-operated-technology-ecosystem/CIT-205-classroom`
   - **base:** `main`
   - **head repository:** your personal fork
   - **compare:** your `article/...` branch
3. Confirm GitHub says the branches can be merged and that the changed file is your Knowledge Article.
4. Select **Create pull request**.
5. In the description, state the scenario, what you verified, and what remains assumed.

If GitHub says you cannot open a pull request because only collaborators may do so, **stop and check the base repository**. You are probably pointing at the protected SOTE operational repository instead of `CIT-205-classroom`.

Your fork is your workspace. Your branch is your change set. The pull request is your proposal. The classroom's `main` branch does not change until the instructor merges it.

## Phase 4 — Peer Review

The instructor assigns a classmate's pull request. Use the [Peer Review Checklist](PEER-REVIEW-CHECKLIST.md).

Provide at least:

- one specific strength;
- one unclear, missing, unsafe, or unsupported point;
- one concrete replacement or addition.

Review the work, not the person. Ask: **Could another technician safely act from this article without guessing?**

## Phase 5 — Revise, Compare, and Publish

1. Respond to the peer feedback.
2. Edit the article on the **same `article/...` branch**.
3. Commit the revision. The existing pull request updates automatically. Do not create a second pull request for the revision.
4. Open the pull request's **Files changed** tab. Green lines were added; red lines were removed. Use this view to prove what changed between versions.
5. After instructor acceptance and merge, open the classroom [Knowledge Base index](../knowledge/README.md) and identify the accepted revision.
6. Open the SOTE Command Portal Knowledge Base. A merged classroom article is published there as **Classroom Accepted** so the class can find and use accepted learning knowledge without entering the protected SOTE framework.

## What the Architecture Is Teaching You

The permissions boundary is intentional:

**Personal fork → article branch → pull request → peer/instructor review → classroom `main` → published classroom knowledge**

The protected SOTE operational framework is a separate layer. Classroom acceptance does **not** automatically make an article an operational SOTE procedure.

This is the same reason organizations separate contributor workspaces, review workflows, published knowledge, and production authority.

## Deliverables

- clarification questions for all six scenarios;
- one Word draft;
- one Markdown Knowledge Article pull request;
- one actionable peer review;
- one revision responding to feedback;
- short reflection: **“Which copy is current, and how can you prove it?”**

## Safety and Privacy

This repository is public. Use fictionalized scenario details only. Never publish credentials, private tickets, student records, real user information, internal network details, or screenshots containing private data.
