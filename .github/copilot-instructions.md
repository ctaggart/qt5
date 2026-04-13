# Qt5 Copilot Instructions

## Branch structure

The `ai` branch is an orphaned branch containing only CI workflows and scripts.
It does not contain Qt source code — Qt source is downloaded at build time from
https://download.qt.io/.

## GitHub account usage

The `ctaggart/qt5` repo is owned by a different GitHub account than `cataggar/qt5`.
To perform admin operations (e.g. changing default branch, dispatching workflows),
switch accounts:

```powershell
gh auth switch --user ctaggart   # for ctaggart-owned repos
gh auth switch --user cataggar   # to switch back
```
