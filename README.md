# 🦣 Mastodoc

*Skill-based, agentic documentation architecture.*

---

**Mastodoc** is the complete self-documentation methodology for your agent bros. It’s an AI-native architecture designed to keep code and documentation in a permanent state of sync. It’s designed to be clean enough for humans to navigate at a glance, and structured precisely for AI agents to understand, maintain, and expand.

## Why Mastodoc?

Traditional documentation rots. It drifts away from the codebase the moment a refactor happens. Mastodoc solves this by treating documentation as a **first-class citizen**—a living knowledge graph maintained by your AI agents during every commit.

## The 3-Level Hierarchy

To keep things simple and navigable as your project scales, we enforce a strict 3-level tree:

1. **[MASTODOC.md](https://www.google.com/search?q=docs/MASTODOC.md) (The Root):** The Master Index. A high-level routing table that maps to your major category branches.
2. **Category Branches (`docs/categories/`):** Contextual hubs for major domains. Each file provides an overview and a list of links to the specific features within that category.
3. **The Leaves (`docs/features/[category]/[feature.md]`):** The "Meat." These files contain the logic, thought process, ADRs, and direct links to your code files.

## For Developers

* **Onboarding:** Start at **[MASTODOC.md](https://www.google.com/search?q=docs/MASTODOC.md)**. You’ll see the high-level architecture at a glance and can dive into specific feature branches as needed.
* **Maintenance:** Documentation is maintained by our AI agents via the **Mastodoc Resync** protocol. If you modify the codebase, you are expected to trigger a resync to keep the leaf nodes updated.

## For Agents

If you are an AI coding assistant (Claude, Cursor, etc.), you are operating within the Mastodoc ecosystem.

* **Before starting:** Refer to `docs/00-META-ARCHITECTURE.md` to understand our constraints and linking standards.
* **After finishing:** Execute the **Mastodoc Resync** protocol. Your task isn't "done" until the relevant Leaf, Category Branch, and Master Index are synced to reflect your changes.

---

*If it’s not documented, it’s not done. Keep the herd in sync.*