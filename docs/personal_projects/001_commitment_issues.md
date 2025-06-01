# Commitment Issues

## Role

**Solo Developer**

## Project Description

A playful script to automate the creation of fake commits in a Git repository for a specified number of past days, simulating commit activity for fun or educational purposes.

## Project Timeline

- **Start Date:** 2025-01-04
- **End Date:** 2025-01-05

## Team Size

1

## Client

Personal

## Keywords

Git, PowerShell, Automation, Scripting, Fake Commits, Personal Project

---

## Tech Stack

- **Script:** PowerShell (create_commits.ps1)
- **Other:** Git

---

## Full Description

Commitment Issues is a lighthearted personal project designed to automate the process of generating fake commits in a Git repository. The PowerShell script, `create_commits.ps1`, prompts the user for the number of days to backdate commits, then iteratively updates a file (`update_file.txt`) and creates a commit for each day in the specified range. This simulates a streak of activity on the Git commit graph, which can be useful for demonstrations, learning, or just for fun.

The script checks that it is run inside a valid Git repository, uses today's date as the starting point, and creates or updates `update_file.txt` with incremental numbers. Each commit is staged and committed with the correct date using Git's environment variables.

**Repository:** [github.com/derekhuynen/Commitment_Issues](https://github.com/derekhuynen/Commitment_Issues)

---

## What I Worked On

- Designed and implemented the PowerShell script to automate commit creation.
- Added logic to check for a valid Git repository before running.
- Implemented user prompts for the number of days to generate commits.
- Automated file updates and commit creation with accurate timestamps.
- Documented usage instructions and script prerequisites.

---

## Challenges & Solutions

- **Challenge:** Ensuring commits are backdated correctly and appear on the intended days.
  - **Solution:** Used Git environment variables to set commit dates programmatically for each commit.
- **Challenge:** Making the script user-friendly and robust for different environments.
  - **Solution:** Added checks for Git repository presence and clear user prompts.
- **Challenge:** Preventing accidental misuse or confusion about the script's purpose.
  - **Solution:** Included clear documentation and a disclaimer about responsible use.

---

## Key Takeaways

- Gained experience with PowerShell scripting and Git automation.
- Learned how to manipulate commit history for educational and demonstration purposes.
- Reinforced the importance of clear documentation and ethical considerations in tooling.
- Had fun experimenting with creative ways to visualize Git activity.

---
