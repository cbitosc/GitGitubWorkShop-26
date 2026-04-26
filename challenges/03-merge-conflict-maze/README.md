# Challenge 03: Merge Conflict Maze (Medium)

## Objective
Create and resolve a merge conflict safely.

## Files
- `poem.txt`

## Task
1. Create branch `poem-feature` from `main`.
2. In `poem.txt`, edit line 2 to:
   - `Git branches split the sky.`
3. Commit on `poem-feature`:
   - `challenge-03: updated poem on feature branch`
4. Switch back to `main` and edit line 2 differently:
   - `Git branches map our way.`
5. Commit on `main`:
   - `challenge-03: updated poem on main`
6. Merge `poem-feature` into `main`.
7. Resolve the conflict by keeping BOTH lines in this order:
   - `Git branches map our way.`
   - `Git branches split the sky.`
8. Finalize merge commit.

## Success Criteria
- Conflict occurs and is resolved manually.
- Final `poem.txt` includes both required lines.
