# gotth-media

> **Distribution:** GitHub is the public clone and, only if implementation is
> admitted later, the future release endpoint.
> Forgejo remains canonical development and the issue/contribution location.
> See [the distribution contract](docs/distribution.md).


Reserved for reusable safe-media and object-storage mechanics shared by GOTTH
applications.

## Intended boundary

This project may eventually own bounded upload streaming, content inspection,
type verification, checksum-addressed objects, quarantine transitions,
derivative generation, storage adapters, and deletion/reconciliation tools.
Consumers retain attachment authorization, quotas, ownership, presentation,
retention decisions, and references from product data.

The project begins only after attachment and large-media requirements define
exact size, format, storage, malware, privacy, and failure contracts.

## Non-goals

- A public file bucket, product attachment model, gallery, or CDN policy.
- Trusting filenames, client MIME types, or image decoder success.
- Deleting an object without consumer-owned reference and retention checks.

## Status

Placeholder only. There is no implementation, API, release, tag, compatibility
promise, or dependency to pin.

## Installation, compatibility, and support

Planned placeholder only. There is no implementation, API, support promise, or
release.

There is nothing to install or import. Do not add this repository as a
dependency.

The repository has no selected license and no long-term support promise.
Versioning, release admission, security reporting, and contribution details are
in [the release policy](docs/RELEASING.md), [security policy](SECURITY.md), and
[contribution guide](CONTRIBUTING.md).
