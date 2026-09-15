# ICV/OSS

**Production Django packages, properly released.**

Open source from Intelligent Commerce Ventures: MIT-licensed packages for
multi-tenancy, UI substrate, host routing, search, sitemaps, taxonomy, trees,
application firewalling and diagnostics. Spec-first, tested against Django 5.2
and 6.0, published to PyPI with trusted publishing and changelog-gated
releases.

**Start at [icvoss.com](https://icvoss.com)** for the package registry, docs and
install guidance. Each package below also has a detail page there.

| No. | Package | On icvoss.com | What it does |
|----:|---------|---------------|--------------|
| 01 | [django-boundary](https://github.com/icvoss/django-boundary) | [docs](https://icvoss.com/packages/django-boundary/) | Row-level multi-tenancy with PostgreSQL RLS |
| 02 | [django-brickwork](https://github.com/icvoss/django-brickwork) | [docs](https://icvoss.com/packages/django-brickwork/) | Brand-agnostic UI substrate for server-rendered Django |
| 03 | [django-hostmap](https://github.com/icvoss/django-hostmap) | [docs](https://icvoss.com/packages/django-hostmap/) | Host-based URL routing and host-aware reversing |
| 04 | [django-icv-core](https://github.com/icvoss/django-icv-core) | [docs](https://icvoss.com/packages/django-icv-core/) | Base models, middleware and audit logging |
| 05 | [django-icv-search](https://github.com/icvoss/django-icv-search) | [docs](https://icvoss.com/packages/django-icv-search/) | Pluggable search with swappable backends |
| 06 | [django-icv-sitemaps](https://github.com/icvoss/django-icv-sitemaps) | [docs](https://icvoss.com/packages/django-icv-sitemaps/) | Background sitemaps and discovery files |
| 07 | [django-icv-taxonomy](https://github.com/icvoss/django-icv-taxonomy) | [docs](https://icvoss.com/packages/django-icv-taxonomy/) | Vocabularies, term trees and tagging |
| 08 | [django-icv-tree](https://github.com/icvoss/django-icv-tree) | [docs](https://icvoss.com/packages/django-icv-tree/) | Materialised path tree structures |
| 09 | [django-waf](https://github.com/icvoss/django-waf) | [docs](https://icvoss.com/packages/django-waf/) | Self-hosted web application firewall |
| 10 | [icv-trace](https://github.com/icvoss/icv-trace) | [PyPI](https://pypi.org/project/icv-trace/) | Bounded operation diagnostics (preview / RC; catalogue entry pending on icvoss.com) |

## How these packages are built

- **MIT, permanently.** No relicensing, no source-available conversions, no CLA assignments.
- **Releases you can audit.** Tags publish through CI with trusted publishing to PyPI; no release ships without tests and a dated changelog entry.
- **Flat by design.** Packages stand alone and compose through PyPI; optional integrations stay optional.

More at **[icvoss.com](https://icvoss.com)**.
