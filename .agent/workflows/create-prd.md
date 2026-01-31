---
description: Create a Product Requirements Document (Phase 2: Planning)
---

# Create PRD (Product Requirements Document)

1. **Prerequisites**
   - Ensure `product-brief` is completed (check `docs/`).
   - Read `bmad-skills/product-manager/SKILL.md` for guidelines.

2. **Context Loading**
   - Read the existing Product Brief.
   - Ask the user for any specific functional or non-functional requirements not yet captured.

3. **Requirements Definition**
   - **Functional Requirements (FR)**: Define what the system does. Assign IDs (e.g., FR-001).
   - **Non-Functional Requirements (NFR)**: Define performance, security, and usability constraints. Assign IDs (e.g., NFR-001).
   - **Prioritization**: Use MoSCoW (Must, Should, Could, Won't) for each requirement.

4. **Epic & Story Breakdown**
   - Group requirements into **Epics**.
   - Draft high-level **User Stories** for each Epic.

5. **Generate PRD**
   - Create `docs/prd-[feature-name]-[date].md`.
   - Include:
     - **Introduction & Scope**
     - **Functional Requirements** (with Acceptance Criteria)
     - **Non-Functional Requirements**
     - **Epics & Stories**
     - **Traceability Matrix** (optional but recommended)

6. **Update Status**
   - Update `docs/bmm-workflow-status.yaml` to mark `prd` as completed.
