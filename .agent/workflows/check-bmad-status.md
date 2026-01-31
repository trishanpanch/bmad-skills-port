---
description: Check the status of the BMAD project and get recommendations for next steps
---

# Check BMAD Project Status

1. **Verify Initialization**
   - Check if `bmad/config.yaml` exists.
   - If not, prompt the user to run the `init-bmad` workflow first.

2. **Read Status**
   - Read `bmad/config.yaml` to get project level and details.
   - Read `docs/bmm-workflow-status.yaml` to see current progress.
   - Scan the `docs/` folder to verify if referenced documents actually exist.

3. **Analyze Progress**
   - Determine the current Phase (Analysis, Planning, Solutioning, Implementation).
   - Identify missing REQUIRED artifacts for the current level.

4. **Report Status**
   - Display a summary of completed items (marked with ✓) and pending items (marked with ⚠ or →).
   - Show the current Project Level and Type.

5. **Recommend Next Actions**
   - Based on the status, suggest the next workflow to run (e.g., "Run 'Create Product Brief'").
