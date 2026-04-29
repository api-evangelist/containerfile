# Containerfile

A Containerfile is a plain text file that contains instructions for building container images. It is fully compatible with Docker's Dockerfile format and is the default file name used by Buildah and Podman. Containerfile instructions describe a base image (FROM), the steps to assemble the image (RUN, COPY, ADD, ARG, ENV), and runtime defaults (CMD, ENTRYPOINT, EXPOSE, USER, WORKDIR, VOLUME). Modern build engines extend the format with cache, secret, and SSH mounts and platform-aware multi-stage builds.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/containerfile/refs/heads/main/apis.yml)

## Tags

- BuildKit, Buildah, Containers, DevOps, Docker, Dockerfile, Image Build, OCI, Podman, Standard

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-04-28

## APIs

### Containerfile Reference
The official Containerfile reference shipped with the containers/common project.

**Human URL:** [Containerfile.5.md](https://github.com/containers/common/blob/main/docs/Containerfile.5.md)

#### Tags
- Containerfile, Reference, containers/common

### Dockerfile Reference
The Dockerfile format reference maintained by Docker. Containerfile is a strict superset of Dockerfile.

**Human URL:** [https://docs.docker.com/reference/dockerfile/](https://docs.docker.com/reference/dockerfile/)

#### Tags
- Docker, Dockerfile, Reference

### BuildKit Dockerfile Frontend
Dockerfile and Containerfile parsing is performed by BuildKit's Dockerfile frontend, distributed as a container image (docker/dockerfile).

**Human URL:** [BuildKit reference](https://github.com/moby/buildkit/blob/master/frontend/dockerfile/docs/reference.md)

#### Tags
- BuildKit, Frontend, Moby

### OCI Image Specification
The Open Container Initiative Image Specification defines the format of the image artifacts produced by Containerfile and Dockerfile builds.

**Human URL:** [https://github.com/opencontainers/image-spec](https://github.com/opencontainers/image-spec)

#### Tags
- Image, OCI, Standards

## Common Properties

- [Containerfile spec](https://github.com/containers/common/blob/main/docs/Containerfile.5.md)
- [Dockerfile reference](https://docs.docker.com/reference/dockerfile/)
- [BuildKit Dockerfile frontend](https://github.com/moby/buildkit/blob/master/frontend/dockerfile/docs/reference.md)
- [OCI](https://opencontainers.org/)
- [GitHub: containers](https://github.com/containers)
- [GitHub: Buildah](https://github.com/containers/buildah)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
