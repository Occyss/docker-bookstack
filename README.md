## Docker Image For [BookStack](https://github.com/ssddanbrown/BookStack)

This fork mainly focus to host multiple BookStack Instances on K8s in subdirectories (wiki.example.com/wiki1, wiki.example.com/wiki2, ...) without root privileges

## Current Version: [21.04.5]

### Changes

Update to bookstack 21.04.5, added more environement variables (mainly for SAML auth) and mainly focus to host on K8s with subdirectory bookstack install (=> Multiple BookStack Instances with Ingress)

### Inspiration

This is a fork of [solidnerd/docker-bookstack](https://github.com/solidnerd/docker-bookstack).
