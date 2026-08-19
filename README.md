# HDR UK GitHub Repository Archiving policy

## Archiving GitHub Repositories

This document sets out HDR UK's guidelines for archiving repositories on GitHub. It is based on GitHub's own guidance on [archiving repositories](https://docs.github.com/en/repositories/archiving-a-github-repository/archiving-repositories), adapted for use across HDR UK projects.

### Why archive a repository?

Archiving a repository marks it as read-only and signals to others that the project is no longer actively maintained. This is the recommended approach for any HDR UK repository that has reached end-of-life, been superseded by another project, or is otherwise no longer being developed, rather than deleting it outright.

Archiving is reversible — a repository can be unarchived at any time if work needs to resume.

### When to consider archiving

HDR UK periodically reviews repositories that may no longer be maintained. A repository may be proposed for archival when **all** of the following apply:

1. It has no licence file.
2. It has had no commits to its main branch in the past two years (with discretion to extend this to three years where appropriate).
3. It has no repository-level administrators beyond HDR UK's default organisation administrators.

As the archiving process is, in principle, lossless (archiving does not delete a repository — it makes it read-only and can be reversed), a repository meeting these criteria does not need to be circulated for wider sign-off before archival. Should corrective action be needed, or the archival need to be reverted, contact one of HDR UK's GitHub administrators.

### Before archiving

Before archiving a repository, repository owners should:

- Close all open issues and pull requests, or transfer any that are still relevant to another active repository.
- Update the README to clearly state that the repository is archived, when it was archived, and where (if anywhere) related or successor work can be found.
- Refresh the repository description so it accurately reflects the project's final status.
- Confirm no automation (CI/CD pipelines, webhooks, integrations) still depends on the repository remaining writable.

### What happens when a repository is archived

Once archived, a repository becomes entirely read-only:

- No new collaborators or teams can be added or removed.
- Issues, pull requests, code, labels, milestones, projects, wiki, releases, commits, tags, branches, reactions, comments, and permissions all become read-only.
- Contributors can still fork or star the repository, but cannot open new issues, pull requests, or comments.
- Any further changes require the repository to be unarchived first.

Archived repositories, along with their issues and pull requests, remain fully searchable and discoverable — archiving does not hide a project, it only freezes it.

### How to archive a repository

1. Go to the repository's **Settings**.
2. Scroll to the **Danger Zone**.
3. Select **Archive this repository**.
4. Confirm by typing the repository name when prompted.
5. Acknowledge the warning to complete the archival.

### How to unarchive a repository

If a repository needs to become active again:

1. Go to the repository's **Settings**.
2. Scroll to the **Danger Zone**.
3. Select **Unarchive this repository**.
4. Confirm by typing the repository name when prompted.
5. Acknowledge the prompt to restore full functionality.

### Organisation-level archiving

Where an entire project or initiative has concluded, all of its associated repositories can be archived together via HDR UK's organisation settings, rather than archiving each repository individually.

### Notes

- Prefer archiving over deletion for any repository with historical, research, or reference value — this preserves provenance and allows future audit or reuse.
- Repository owners should periodically review inactive repositories against these guidelines and propose archival where appropriate.
