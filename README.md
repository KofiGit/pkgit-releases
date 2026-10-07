# PkGit

**A free desktop Git client for Linux and Windows.**

PkGit shows your repositories as a clear commit graph and lets you do everyday Git work with a few clicks: stage, commit, branch, merge, rebase, pull and push, with GitHub sign-in and pull requests built in.

**[⬇ Download the latest version](https://github.com/KofiGit/pkgit-releases/releases/latest)**

## Features

- **History:** commit graph with details and diffs, fast even with 100k+ commits; search by text, `author:` and `file:`
- **Working tree:** stage, unstage and discard by file, hunk or line; commit and amend; built-in conflict editor; side-by-side diff
- **Branches:** create, switch, rename, delete, merge (fast-forward, no-ff, squash); stash, tags, cherry-pick, revert
- **History rewriting:** rebase, interactive rebase (reorder, reword, squash, fixup, drop), reset, undo/redo
- **Inspect:** file history, blame, compare two revisions
- **Remotes:** fetch, pull, push with progress and cancel; clone; auto-fetch; HTTPS and SSH credential prompts
- **GitHub:** sign in with your GitHub account; list, view, create and check out pull requests
- **Comfort:** tabs for several repositories, live updates, dark and light themes, customizable keyboard shortcuts
- **Auto-update:** PkGit checks for new versions and offers to install them

## Download and install

Open the [latest release](https://github.com/KofiGit/pkgit-releases/releases/latest) and pick the file for your system:

| System | File |
|---|---|
| Windows (x86_64) | `PkGit_<version>_x64-setup.exe` (recommended) or `.msi` |
| Linux, any distribution | `PkGit_<version>_amd64.AppImage` |
| Debian / Ubuntu | `PkGit_<version>_amd64.deb` |
| Fedora / openSUSE | `PkGit-<version>-1.x86_64.rpm` |

**Requirement:** PkGit uses the Git installed on your system. If you don't have it, install [Git](https://git-scm.com/downloads) first.

**Windows:** the installer is not code-signed yet, so SmartScreen shows a warning. Click **More info → Run anyway**.

**Linux AppImage:** make the file executable and start it:

    chmod +x PkGit_*_amd64.AppImage
    ./PkGit_*_amd64.AppImage

macOS is not supported yet.

## Updates

PkGit checks this page for new versions and offers to install them (Settings → Help). The AppImage and the Windows version update themselves; with `.deb` or `.rpm`, install the new package from the latest release.

## Using GitHub

Sign in under **Settings → Accounts**. To fetch, pull or push a GitHub repository, give PkGit access to it there with **Choose repositories**. Without that, GitHub answers "Write access to repository not granted".

## Help and feedback

- In the app: **Settings → Help → Report a problem** (includes the recent log lines)
- [Open an issue](https://github.com/KofiGit/pkgit-releases/issues)
- E-mail: [propkeu@proton.me](mailto:propkeu@proton.me)

## Licence

PkGit is **freeware**: free to use, privately and commercially. The source code is not public. This repository only holds the releases. Open-source components used by PkGit are listed in the app under Settings → Help → Open-source licences.

## Support PkGit

PkGit is free. If it helps you, you can support its development on **[Ko-fi](https://ko-fi.com/propk)**. Thank you!
