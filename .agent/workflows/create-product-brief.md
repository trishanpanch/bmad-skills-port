---
description: Create a Product Brief (Phase 1: Analysis)
---

# Create Product Brief

1. **Prerequisites**
   - Ensure the project is initialized (`bmad/config.yaml` exists).
   - Read `bmad-skills/business-analyst/SKILL.md` (if available) for detailed guidelines.

2. **Discovery (Interactive)**
   - Interview the user to gather requirements. Use the **Discovery Question Framework**:
     - **Problem**: What problem are we solving? Who experiences it?
     - **Solution**: What is the proposed solution? Key capabilities?
     - **Success**: How will we measure success? Target metrics?
   - *Note: Be diligent. Do not proceed until you have clear answers.*

3. **Research (Optional/Agentic)**
   - If the user requests market research or competitive analysis, use the `search_web` tool to gather data.
   - Synthesize findings into the brief.

4. **Draft Product Brief**
   - Create a new file `docs/product-brief-[features-name]-[date].md`.
   - Structure:
     - **Problem Statement**
     - **Target Audience**
     - **Proposed Solution**
     - **Key Features**
     - **Success Metrics**
     - **Risks & Mitigation**

5. **Update Status**
   - Update `docs/bmm-workflow-status.yaml` to mark `product-brief` as completed (provide the filename).
