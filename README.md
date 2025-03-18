# Build Container Image

This action builds a container image based on [pull request git ref](https://github.com/docker/metadata-action?tab=readme-ov-file#typeref) data, then pushes it to the specified registry.

## Required Inputs

- registry:
  - description: Hostname (not URL) of image registry
  - required: true
- registry_repo: 
  - description: Project/component of image, i.e. cms/admin
  - required: true
- registry_user:
  - description: Username for registry auth
  - required: true
- registry_pass:
  - description: Password for registry auth
