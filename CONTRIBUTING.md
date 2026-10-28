# Contributing

## The rule everything else follows

A change is worth merging when it carries evidence that it does what it says. In this
account that means a test that **fails before the change and passes after it** — not a
test that merely exists next to the change.

## Before you open a pull request

1. Reproduce the problem on the current default branch and keep the output. If it did
   not reproduce, do not open the PR yet.
2. Write the failing test first, run it against the unmodified source, and quote the
   failure in the PR.
3. Fix the smallest thing that makes it pass. Put unrelated cleanup in its own PR.
4. Run the repository's own checks. Each README states its test command; nothing here
   has a hidden one.
5. Say in the PR body what you verified **and what you did not**. "Not tested on
   Windows" is useful; silence is not.

## What gets closed

- A description that claims a result the diff or the checks do not show.
- A fix bundled with reformatting or with a second unrelated fix.
- A change that makes a check pass by narrowing what the check reads.

## Style

Run the formatter the repository already uses. Commit messages state what changed and
why, in the present tense; a commit that only says "fix" is a commit that will be read
twice.
