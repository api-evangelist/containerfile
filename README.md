# Containerfile

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
