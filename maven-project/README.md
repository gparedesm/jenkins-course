# Install Git and Maven Plugin
Go to `Manage Jenkins - Manage Plugins` and install: Git and Maven plugins.

# Add Maven
1. Go to `Manage Jenkins - Global Tool Configuration - Maven - Add Maven`
2. Check Install automatically.
3. Save

# Add maven build to the job
Go to build section, and add `Invoke Top-Level Maven targets`. Then, in goals section, copy this: `-B -DskipTests clean package`.

## Add Test step
Go to build section and add after build section created before, other similar step `Invoke Top-Level Maven targets`. Then, in goals section, copy this: `test`.
