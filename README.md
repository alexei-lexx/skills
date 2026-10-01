# alexei-lexx-skills

Agent skills for developers.

## Install

### Claude Code

From the terminal:

```bash
claude plugin marketplace add alexei-lexx/skills
claude plugin install alexei-lexx-skills@alexei-lexx
```

Or inside a Claude Code session:

```
/plugin marketplace add alexei-lexx/skills
/plugin install alexei-lexx-skills@alexei-lexx
```

### Any agent

Use the [skills](https://github.com/vercel-labs/skills) CLI:

```bash
npx skills add alexei-lexx/skills
```

## Skills

- `address-review-comments`: works through PR review comments one by one and helps fix or reply
- `finish-up`: runs final checks, then lands the branch and commits
- `format-git-commit`: drafts a commit message from the current changes
- `format-github-issue`: formats a GitHub issue title and description
- `format-github-pr`: formats a GitHub pull request title and description
- `interview`: gathers input from the user through a series of questions
- `teach-me`: teaches or recaps a topic in small steps, from basics to advanced
- `testing`: guides writing and reviewing Jest or Vitest tests
