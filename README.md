## Docker Image For [BookStack](https://github.com/ssddanbrown/BookStack)

This fork mainly focus to host multiple BookStack Instances on K8s in subdirectories (example.com/wiki1, example.com/wiki2, ...) without root privileges

## Current Version: [v21.10.3]

### Changes

Update to bookstack v21.10.3, added more environement variables (mainly for SAML auth) and mainly focus to host on K8s with subdirectory bookstack install (=> Multiple BookStack Instances with Ingress)

### Inspiration

This is a fork of [solidnerd/docker-bookstack](https://github.com/solidnerd/docker-bookstack).
