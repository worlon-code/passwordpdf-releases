# Release Retention Rules

In order to manage repository size, we maintain a strict retention policy for APK releases.

## Policy
We keep a maximum of **3 versions** in the `releases/` directory:

1.  **Current Release** (The latest version)
2.  **Previous Release** (The one before current)
3.  **Pre-previous Release** (The one before previous)

**Action**: Any version older than these three MUST be deleted when a new release is published.
