# Upload-Artifact v2

This uploads artifacts from your workflow allowing you to share data between jobs and store data once a workflow is complete.

See also [download-artifact](https://github.com/actions/download-artifact).

# What's new

- Easier upload 
  - Specify a wildcard pattern
  - Specify an individual file
  - Specify a directory (previously you were limited to only this option)
  - Multi path upload
    - Use a combination of individual files, wildcards or directories
    - Support for excluding certain files
- Upload an artifact without providing a name
- Fix for artifact uploads sometimes not working with containers
- Proxy support out of the box
- Port entire action to 
