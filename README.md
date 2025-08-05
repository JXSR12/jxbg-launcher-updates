# JXBG Launcher Updates Repository

This repository manages update files for the JXBG Launcher.

## How to Release Updates

1. Place your update files in this repository
2. Create a new `update.zip` file containing all the files to be updated
3. Commit and push your changes
4. Create a new release on GitHub with the `update.zip` file attached
5. Tag the release with a version number (e.g., `v1.0.0`, `v1.1.0`, etc.)

## Directory Structure

```
jxbg-launcher-updates/
├── README.md
├── .gitignore
└── releases/
    └── (place your update files here before zipping)
```

## Updater Scripts

The updater scripts will automatically:
1. Download the latest `update.zip` from GitHub releases
2. Extract the contents to the launcher directory
3. Replace existing files with new versions

## Version Information

- Current version will be tracked in releases
- Each release should include detailed changelog
- Use semantic versioning (MAJOR.MINOR.PATCH)