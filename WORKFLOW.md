# A small, repeatable work session

1. **Pick a concrete outcome.** Fix one bug, explain one equation, improve one interaction, or complete one project step.
2. **Do the work.** Keep changes focused. Use a branch when a change needs review or experimentation.
3. **Check the result.** Run the project’s documented checks and inspect the affected behavior. Record limits honestly.
4. **Leave evidence.** Add a brief work-log entry with the result, a test or demo, something learned, and the next step.
5. **Review before sharing.** Check the diff and staged files. Keep credentials, private contact details, client information, and employer material out of public repositories. Publish work only where you have permission.
6. **Commit and push.** Describe the actual result in the commit message. No empty commits or backdated activity to manufacture a streak.

For a repository you already work in:

```sh
git status
git diff
# Stage only the files belonging to the change:
git add path/to/changed-file
git diff --cached
git commit -m "Describe the useful change"
git push
```

Before the first commit on a new machine, configure your name and the GitHub-provided no-reply address shown in your own account’s email settings. A repository’s local Git settings can override global settings.

## What makes good portfolio evidence?

- A working demo and instructions another person can follow.
- A problem, the chosen approach, and why it was chosen.
- A meaningful test, measurement, or before-and-after comparison.
- An honest account of collaboration and AI assistance.
- A clear explanation of what you would improve next.

Private work can contribute to GitHub’s activity totals without exposing its contents. Contribution totals are one signal; the quality and explanation of the work matter more.
