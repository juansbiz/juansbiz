# Contributing to projects maintained by Juan and HIFICOPY

Thank you for contributing. This policy explains where development happens and how to propose a change without losing work.

## One canonical forge

The canonical source for projects maintained by Juan and HIFICOPY is:

**https://git.antieq.com**

GitHub repositories bearing the same names are public mirrors used for discovery, release visibility, and community discussion. Do not open code contributions on GitHub. GitHub pull requests and issues may be disabled, and commits made only on a GitHub mirror can be overwritten by the next Forgejo synchronization.

If a project maintained by somebody else is canonical on GitHub, GitLab, Codeberg, or another forge, contribute there instead. This policy applies only to projects maintained by Juan or HIFICOPY.

## What requires an account

You can browse, clone, and download public repositories without an account.

Create an account on `git.antieq.com` when you want to:

- open or comment on an issue;
- fork a repository;
- submit or review a pull request;
- participate in project planning.

Contributor accounts may fork maintained repositories but cannot create unrelated repositories or organizations on this instance.

## Before changing code

1. Read the repository's `README.md`, `CONTRIBUTING.md`, `SECURITY.md`, and license.
2. Search existing issues and pull requests.
3. Open an issue before substantial work so maintainers can confirm scope.
4. Small documentation, typo, and clearly isolated bug fixes may go directly to a pull request unless the repository says otherwise.

## Contribution workflow

1. Fork the canonical repository on Forgejo.
2. Clone your fork.
3. Add the canonical repository as `upstream`.
4. Create a focused branch.
5. Make the smallest complete change.
6. Run the repository's documented checks.
7. Push to your fork and open a Forgejo pull request.

Example:

```bash
git clone https://git.antieq.com/YOUR_USERNAME/PROJECT.git
cd PROJECT
git remote add upstream https://git.antieq.com/OWNER/PROJECT.git
git switch -c fix/short-description
# make and verify the change
git push -u origin fix/short-description
```

Open the pull request against the canonical repository's default branch.

## Pull-request expectations

A useful pull request:

- explains the problem and why the change is needed;
- links the relevant issue when one exists;
- separates shipped behavior from proposals or roadmap work;
- includes tests or explains why a test is not applicable;
- updates user-facing documentation when behavior changes;
- contains no credentials, customer data, private hosts, production values, or generated clutter;
- is small enough to review responsibly.

Maintainers may ask for a change to be split, revised, or closed when it conflicts with project scope.

## Agent-assisted contributions

Agentic tools are welcome. Contributors remain responsible for every submitted line.

When an agent materially helped produce a change:

- read the complete diff;
- run the relevant tests and checks yourself;
- remove fabricated claims, dependencies, and unsupported behavior;
- disclose material agent assistance in the pull-request description;
- explain what was verified by a human;
- never include prompts, transcripts, credentials, or private context unless the repository explicitly requests a safe artifact.

"An agent wrote it" is not evidence that a change is correct. The contributor who submits the pull request owns the result.

## Reviews and merges

Passing automation is required where checks exist, but automation does not replace review. Maintainers decide what merges and may require approval, test evidence, security review, or documentation before accepting a change.

Do not force-push after review begins unless a maintainer asks you to rewrite history. Add follow-up commits so reviewers can see what changed.

## Security and conduct

Do not report vulnerabilities in public issues or discussions. Follow the repository's `SECURITY.md`. If no security policy exists, contact the maintainer privately before disclosing details.

Participation is governed by each repository's `CODE_OF_CONDUCT.md`.

## Licensing

By submitting a contribution, you agree that it may be distributed under the repository's existing license. Review the license before contributing.
