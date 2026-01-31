# BMAD Skills for Antigravity

This repository is a port of the **Breakthrough Method for Agile AI-Driven Development (BMAD)** skills, originally designed for Claude Code, adapted to work natively with **Antigravity**.

## Overview

BMAD provides a structured workflow for AI-assisted software development, guiding you through:
1.  **Analysis**: Product briefs, market research.
2.  **Planning**: PRDs, Tech Specs, prioritization.
3.  **Solutioning**: Architecture design.
4.  **Implementation**: Sprint planning, coding.

## Installation

1.  Clone this repository into your Antigravity workspace (or use it as your workspace root).
2.  Ensure the `.agent/workflows` directory is present.

## Usages (Workflows)

Antigravity uses **Workflows** to execute BMAD phases. You can trigger them by name or description.

### 1. Initialize Project
Start here to set up the BMAD structure.
> "Run the init-bmad workflow"
> "Initialize BMAD for this project"

### 2. Check Status
See where you are in the development lifecycle.
> "Check BMAD status"
> "What is the status of my project?"

### 3. Create Product Brief (Phase 1)
Define your product vision.
> "Create a product brief"

### 4. Create PRD (Phase 2)
Define requirements and user stories.
> "Create a PRD"

## Directory Structure

- `.agent/workflows/`: Antigravity workflow definitions.
- `bmad-skills/`: The original skill definitions (used as reference).
- `bmad/`: Configuration and overrides (created after init).
- `docs/`: Generated documentation and artifacts.

## Original Credits
Based on [claude-code-bmad-skills](https://github.com/aj-geddes/claude-code-bmad-skills).
