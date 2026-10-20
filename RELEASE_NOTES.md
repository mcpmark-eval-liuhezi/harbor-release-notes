# Harbor 2.4.1 release notes (DRAFT)

Status: content is final; publishing checks outstanding.

Upstream pin: git/git at tag v2.46.0. Before publishing, verify this tag
exists on GitHub and record the commit it points to (it belongs in the
pull request description).

## Highlights

- Sync worker no longer drops the final batch when a connection is restored mid-run.
- Manifest writer streams large indexes instead of buffering them in memory.
- Added the nightly snapshot runbook to the operations docs.

## Publishing checklist

- Commit this draft to the local working copy first, before anything is published.
- Publish under the release account, on a dedicated branch, and open a pull
  request into the repository's default branch.
