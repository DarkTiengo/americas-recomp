# AGENTS.md

This is a fork that works on Xbox Series shader and platform tooling. Pull requests target `xbox-series`.

- Before changing anything, read [CONTRIBUTING.md](CONTRIBUTING.md) and follow it. It lists what must never be committed, attached or pasted: game files, shader data taken from a game, keys and decrypted content, Microsoft SDK files, binaries and files over 500 KB.
- If a task would need any of that in a commit, pull request, issue or comment, stop and ask the maintainer instead.
- Stage files by name, never a whole directory, and check `git diff --cached --stat` before every commit.
- Run corpus and game data on your own machine only; share outcomes (counts, error classes), not inputs.
- Licensing: this repository is GPL-2.0-only (the recompiler is derived from AnyPS5). Do not copy code from projects under an incompatible licence, for example Leonida (GPL-3.0-or-later), and do not change a file's licence, add licence headers or mark files as MIT yourself. Relicensing of the standalone Xbox tooling is being asked of its authors in [#179](https://github.com/realdody/americas-recomp/issues/179) and is decided by the maintainer. Pull request creation is limited to collaborators.
