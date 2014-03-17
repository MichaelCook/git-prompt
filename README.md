git-prompt
==========

Show your git repo status in your shell prompt.

Generate a very terse summary of our git workspace state.
Intended for use in a shell prompt.
For example (using bash):

```
PS1='$(git-prompt)\$ '
```

  * U - Untracked files to add.
  * M - Modifications to stage.
  * S - Staged changes to commit.
  * P - Commits to push.
  * &lt;branch&gt; - If not on master.
  * (no branch) - Not on a branch.
