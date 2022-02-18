# Commit Messages
A detailed note on writing good git commit messages can be found [here](https://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html).

# Branching
- Branch names should be lowercase and hyphenated. eg: `pose-estimation`
- Personal branches should be prefixed with `<username>-`. 
- Other contributors should not push changes to personal branches. Collaboration should be restricted to shared branches only.

# Pushing Changes
- Do not push directly to `main` branch.
- Do not force push (`git push --force`) to shared branches. However, force pushes are permitted to personal branches.
- Using fast-forward merges are strongly recommended wherever possible. 
- Rebase your local changes before submitting a pull request.

# Asking for help
- Search for your problem on StackOverflow and use the official [Git documentation](https://git-scm.com/docs) to verify.
- When in doubt, create a backup of your branch using `git branch backup`  before running arbitrary git commands from the internet.
- [DangItGit](https://dangitgit.com/en) is a great resource for when you mess up with git.

