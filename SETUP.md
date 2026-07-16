# Bloca Workspace
This repository is a workspace for the Bloca project family. It contains the shared sync script at the root and several product-specific repositories in sibling folders (see the main [`README.md`](./README.md) for the full list of repos).

## Syncing repositories
Use the root script to clone missing repositories or pull updates for existing ones:

```bash
./git-sync.sh
```

The root `Makefile` provides the same action:

```bash
make sync
```

## Notes

The sync script expects GitHub access to the `integratech-org` repositories listed in `git-sync.sh`.
