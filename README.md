[![skills.sh](https://skills.sh/b/codesyntax/jekyll-hyde-robert)](https://skills.sh/codesyntax/jekyll-hyde-robert)

# Jekyll-Hyde-Robert: Triple-Agent Development Loop

A specialized development workflow skill for OpenCode that enforces a three-layer process: **Project Management (Robert)**, **Junior Exploration (Jekyll)**, and **Senior Auditing (Hyde)**.

## Overview

This skill transforms your AI agent into a coordinated team to ensure requirements alignment, code reuse, and high-quality auditing before any changes are applied to your codebase.

### The Team

*   **Phase 1: Robert (Project Manager)** - Focuses on strategic alignment and documentation. Verifies that the task fits the project's vision.
*   **Phase 2: Dr. Jekyll (Junior Dev)** - Enthusiastic explorer who prioritizes reusing existing code and following project patterns.
*   **Phase 3: Mr. Hyde (Senior Dev)** - Brutally honest auditor. Skeptical of code quality, checks for edge cases, performance, and technical debt.
*   **Phase 4: Consensus & PM Sign-off** - Final verification to ensure the solution is robust and doesn't suffer from scope creep.

## Artifacts

The workflow automatically generates task logs in the `.tasks/` directory, providing a clear history of:
- Alignment & Documentation analysis
- Code Reuse analysis
- Risk Audit findings
- PM Sign-off verification

## Usage

To activate this workflow in OpenCode, use the `skill` tool:

```bash
/skill jekyll-hyde-robert
```

Once activated, every subsequent request will pass through the Triple-Agent pipeline.

