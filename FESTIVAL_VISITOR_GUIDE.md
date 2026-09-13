# Festival Visitor Guide

## Student Information

- Name: Oury Ly
- Course and section: CSC350-1300
- Date: 09/12/2026

## Repository Evidence

- Current branch: Branch name
- Personal Homework 2 GitHub URL: https://github.com/lyourybailo082-hash/CSC350-HW2-lyourybailo082-hash.git
- Starting `git status`: On branch main, nothing to  commit, working tree clean
- Starting preparation commit ID: bd125dd

## Festival Identity

- Festival name: Global Culture Festival
- Location: BMCC Campus, New York City
- Intended audience: College students and community members
- Theme: A celebration that brings people together through culture, music, food, and community.

## Prediction Before the First Commit

1. Where does the saved change currently live?

   In the working directory(working tree)

2. Has it been staged or committed?

  No, it has not been staged or committed yet

## Arrival Information

- Transit or parking: Take the subway or bus to the BMCC Campus
- Entrance or meeting location: Meet at the main entrance of the BMCC Campus.

## Accessibility Information

1. Wheelchair-accessible entrances and elevators are available.
2. accessible seating will be available for visitors who need it.

## Visitor Reminder

Please respect other visitors and follow Campus Safety rules.

## GitHub Verification

GitHub verification completed by lyourybailo082-hash

## Commit Evidence

| Checkpoint | Short commit ID | Required message |
|---|---|---|
| Personalized guide | 5ffc8e2 | `docs: personalize festival visitor guide` |
| Visitor access information |  0372618 | `docs: add visitor access information` |
| GitHub verification | 2cc102d | `docs: verify independent homework on GitHub` |
| Final reflection | [09f606d] | `docs: complete independent Git reflection` |

## Individual Reflection

1. What is the difference between saving a file and committing it?

   Saving a file only changes the working copy in the editor. A commit records the staged snapshot in the Git repository history.

2. What is the difference between `git diff` and `git diff --staged`?

   `git diff` shows unstaged changes between the working tree and the index. `git diff --staged` shows staged changes between the index and the last commit.

3. Why did the GitHub verification sentence not appear locally before `git pull`?

   The sentence was created in the GitHub web editor, so GitHub created a remote commit that the local repository had not fetched yet. `git pull` brought that remote commit into the local branch.

4. What did `-u` accomplish in `git push -u origin main`?

   `-u` set the upstream tracking relationship for the local `main` branch to `origin/main`. After that, `git pull` and `git push` could use the branch’s remote automatically.

5. What evidence proves that the local and GitHub repositories are synchronized at the end?

   `git status` shows a clean working tree and `git log` on the local branch matches the GitHub branch history. The final local `main` and `origin/main` have the same newest commit ID.

 
