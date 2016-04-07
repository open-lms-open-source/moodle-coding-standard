# How to update the standard

To sync with [moodle-local_codechecker](https://github.com/moodlehq/moodle-local_codechecker), first review
the [update-standard](../bin/update-standard) command and make sure it is grabbing the correct version from git.
Then issue the following commands:

```
cd /path/to/root/of/this/project
bin/update-standard BRANCH_OR_TAG
... Review changes to moodle and PHPCompatibility directories
git commit
```

Also commit any changes or improvements to `bin/update-standard` command.