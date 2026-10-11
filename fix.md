## Ticket

<!-- Link the approved ClickUp/Linear ticket. -->

- **Ticket ID:** mando-316
- **Ticket title:** fix non-functional read more links in article card

## Team lead

<!-- @handle of your team lead. They review and approve before Zedu reviewers pick this up. -->

@Sodiqbinaliu

## What changed
Removed a non-functional read-more button in the article card in:


<!-- Short summary of the change. -->

## Why
All the text in the card is already on the screen for the user to see so there was nothing more to read thereby making it useless and non-functional.
The read-more buttons highlighted in the screenshot below are non-functional

<img width="959" height="450" alt="Before read-more buttons were removed" src="https://github.com/user-attachments/assets/a889643e-b933-49c6-98e0-af1e4994c7d4" />

<!-- The problem or reason this ticket exists. -->

## How to test

<!-- Numbered steps a reviewer can follow to verify the change themselves. -->

1. Run the app like you normally would

## What to expect

Notice that the read-more buttons do not appear there anymore

<img width="959" height="450" alt="Screenshot 2026-10-10 012342" src="https://github.com/user-attachments/assets/d5972adb-8ea3-4b37-9446-8d93d876d576" />
<!-- The expected behaviour after following the steps above. -->

## Backend

<!-- Leave this section empty: your preview runs against the dev backend.
     Only if this PR needs backend work that isn't on dev yet, add a line here starting with "Backend URL:"
     followed by that backend's host, for example https://api.<team>.groups.zedu.chat. The Backend dependency
     check then blocks merging until the backend lands on dev and you delete the line. -->

## Test evidence

<!-- The Fork build check reports the build result automatically. Say which backend you tested against,
     and whether tests were added or updated for what this ticket changed (and why not, if not). -->

- Tested against:
- Tests:

## Mandatory checks

- [x] **Atomic:** one logical change, at most ~400 lines of meaningful code (lockfiles and generated files like `*.tsbuildinfo` don't count). Larger needs a `size-override` label from a reviewer.
- [x] **Database / API contract:** schema changes follow Expand-Contract — no destructive drops or renames.
- [x] **Preview:** I checked the change in the PR's preview (or ran it locally, if the PR has no preview).
- [x] **Protected files:** I did not change `.github/`, `AGENTS.md`, `CONTRIBUTING.md` or tooling config without reviewer agreement and the `config-change-approved` label.

## Screenshots / recording

<!-- Required for visible or interactive changes. Otherwise write "N/A, non-visual change". -->

## Checklist

- [x] Linked to an approved ticket
- [x] Only indended files changed
- [x] No secrets or debug code committed
- [x] Tests added/updated for what this ticket changed (not retroactive coverage of unrelated code)
- [x] Team lead approved this PR
- [x] Self-reviewed (`git status` / `git diff`)
