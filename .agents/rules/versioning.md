# Versioning and Release Rule

Every time changes/fixes are pushed to Git for this repository:
1. **Bump the Patch Version** in `package.json` (e.g. `1.0.1` -> `1.0.2`).
2. **Update `CHANGELOG.md`** with the new version section and description of changes.
3. **Create and push a Git tag** (e.g. `v1.0.2` with `git push origin --tags`) matching the new version.
