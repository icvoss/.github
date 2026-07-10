# ICV/OSS

**Production Django packages, properly released.**

Open source from Intelligent Commerce Ventures: MIT-licensed packages
covering multi-tenancy, search, sitemaps, taxonomy, tree structures, and
application firewalling. Spec-first, tested against Django 5.2 and 6.0,
published to PyPI with trusted publishing and changelog-gated releases.

**[icvoss.com](https://icvoss.com)** is the package registry and
documentation site.

| No. | Package | What it does |
|----|---------|--------------|
| 01 | [django-boundary](https://github.com/icvoss/django-boundary) | Row-level multi-tenancy with PostgreSQL RLS |
| 02 | [django-icv-core](https://github.com/icvoss/django-icv-core) | Base models, middleware, audit logging |
| 03 | [django-icv-search](https://github.com/icvoss/django-icv-search) | Pluggable search with swappable backends |
| 04 | [django-icv-sitemaps](https://github.com/icvoss/django-icv-sitemaps) | Background sitemaps and discovery files |
| 05 | [django-icv-taxonomy](https://github.com/icvoss/django-icv-taxonomy) | Vocabularies, term trees, and tagging |
| 06 | [django-icv-tree](https://github.com/icvoss/django-icv-tree) | Materialised path tree structures |
| 07 | [django-waf](https://github.com/icvoss/django-waf) | Self-hosted web application firewall |

## How these packages are built

- **MIT, permanently.** No relicensing, no source-available conversions, no CLA assignments.
- **Releases you can audit.** Tags publish through CI with trusted publishing to PyPI; no release ships without tests and a dated changelog entry.
- **Flat by design.** Packages stand alone and compose through PyPI; optional integrations stay optional.
