# git commit

The command `git commit` will take all tracked changes (items added with [git add](./add.md)) and package them up in what is called a commit.

Commits come with commit messages that are required for each commit. You add a message to a commit command by using the `-m` flag followed by a message in quotes.

A commit message _can_ be anything, but best practices dictates that you should use that message to indicate the changes included in the commit.

For example, when we add the ability for a user to provide a picture, then you might have a variation of the following:

```
git add.
git commit -m "Added user picture functionality"
```
Then when viewing the history of a git repository, you can pinpoint where the registration functionality was added.

## Resources
- [Git Commit Documentation](https://git-scm.com/docs/git-commit)

---
[Back to home](../README.md)
