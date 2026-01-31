---
description: Initialize BMAD (Breakthrough Method for Agile AI-Driven Development) for this project
---

# Initialize BMAD Method

1. **Check for existing configuration**
   - Check if `bmad/config.yaml` exists.
   - If it exists, inform the user and stop.

2. **Collect Project Information**
   - Ask the user for the **Project Name**.
   - Ask the user for the **Project Type** (e.g., `web-app`, `mobile-app`, `api`, `library`, `game`, `other`).
   - Ask the user for the **Project Level** (0-4):
     - Level 0: Single atomic change
     - Level 1: Small feature (1-10 stories)
     - Level 2: Medium feature set (5-15 stories)
     - Level 3: Complex integration (12-40 stories)
     - Level 4: Enterprise expansion (40+ stories)

3. **Create Directory Structure**
   - Create directories: `bmad/agent-overrides`, `docs/stories`, `docs/architecture`.

4. **Create Configuration File**
   - Create `bmad/config.yaml` with the collected information.
   - Use the standard template structure (refer to `bmad-skills/bmad-orchestrator/templates/config.template.yaml` if available, or generate a sensible default).

5. **Create Workflow Status File**
   - Create `docs/bmm-workflow-status.yaml`.
   - Set initial status based on Project Level:
     - **Phase 1 (Analysis)**: Recommended for all.
     - **Phase 2 (Planning)**: 
       - PRD: Required for Level 2+, Recommended for Level 0-1.
       - Tech Spec: Required for Level 0-1, Optional for Level 2+.
     - **Phase 3 (Solutioning)**: Architecture Required for Level 2+, Optional for others.
     - **Phase 4 (Implementation)**: Required for all.

6. **Finalize**
   - Display a summary of the initialized project.
   - Recommend the next step (usually `create-product-brief` for Analysis phase).
