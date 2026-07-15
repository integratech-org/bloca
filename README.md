# Bloca Workspace

This repository is a workspace for the Bloca project family. It contains the shared sync script at the root and several product-specific repositories in sibling folders.

## What’s here
- [`bloca-admin/`](https://github.com/integratech-org/bloca-admin) - admin dashboard
- [`bloca-api/`](https://github.com/integratech-org/bloca-api) - backend API
- [`bloca-firmware/`](https://github.com/integratech-org/bloca-firmware) - firmware sources
- [`bloca-landing/`](https://github.com/integratech-org/bloca-landing) - marketing site
- [`bloca-ml/`](https://github.com/integratech-org/bloca-ml) - machine learning components
- [`bloca-mobile/`](https://github.com/integratech-org/bloca-mobile) - mobile app

## Syncing repositories

Use the root script to clone missing repositories or pull updates for existing ones:

```bash
./git-sync.sh
```

The root `Makefile` provides the same action:

```bash
make sync
```
