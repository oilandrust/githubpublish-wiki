**2026-07-23: Release 0.1.35**
This release fixes a few issues, notably that **Canvases** are now rendered properly; they were previously ignored. Also, the modified pages were showing an incorrect date for the **modified date field**. Now the dates correctly show the last time a note was modified, not the last time the site was updated.

Additional details for release 0.1.35:
- Automatically sync the publish toolchain (deploy workflow, lockfile, and related files) on Publish changes when it drifts from the plugin.
- Fix page “modified” dates: Quartz now builds with `-d` against the site content checkout so dates come from git history instead of identical CI copy timestamps.

**2026-07-07: Release 0.1.24**
This release allows you to configure the Quatz site generator. The configuration can be edited in the plugin settings.
Changes in the configuration are detected and can be published just as new content is published.

![[edit_config.png|300]]

**2026-07-06: Release 0.1.23**
Requires disconnecting the GitHub account and acquiring a new GitHub authentication token through the login flow.
The app asks for public repositories only, not private repositories as it used to.
