# Feature: Spaced Repetition

## 1. Overview & Logic
Brief explanation of what the feature does and the core business logic with internal codebase pointers.

## 2. Codebase Pointers
Where to find the moving parts for this feature: (pointers live both here and in the ## 1. Overview & Logic section)
* **Frontend UI:** [`lib/features/repetition/screens/`](../../lib/features/repetition/screens/)
* **Backend API:** [`app/routers/repetition.py`](../../app/routers/repetition.py)
* **Graph Queries:** [`app/db/queries/spaced_rep.cypher`](../../app/db/queries/spaced_rep.cypher)

## 3. Usage Examples
Code snippets showing how to call the API or instantiate objects.

## 4. Ideas & TODOs
* [ ] Override interval dynamically based on user streak.
* *Idea:* Add a karma point multiplier for weekend reviews.