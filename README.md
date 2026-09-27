# Pair Attribution Demo

A small demo repository for documenting collaboration workflows.

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/audition-mld/pair-attribution-demo.git
   ```
2. Make changes on a focused branch.
3. Open a Pull Request into `main`.
4. Merge with a merge commit so individual commits keep their original authorship.

## Contributing

- Keep changes small and focused.
- Describe the actual improvement in the Pull Request description.
- Use `git log --pretty=full` to verify authorship before pushing.

## Collaboration Guidance

When working together, agree on authorship before pushing:

- The person writing the change commits as the primary author.
- Add any pair partner with a `Co-authored-by` trailer at the end of the commit message, preceded by a blank line.
- Verify with `git show -s --format=fuller HEAD` that the author email uses the GitHub `users.noreply.github.com` address so GitHub links both profiles.
- Open a Pull Request and merge with a merge commit so the original co-authored commit stays intact on `main`.
