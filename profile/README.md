<h1 align="center">FORKTEX</h1>

<p align="center">
  <b>We build software that ships.</b><br>
  A software engineering firm in Bucharest, working for companies across Europe and North America since 2021.
</p>

<p align="center">
  <a href="https://forktex.com">Website</a> ·
  <a href="https://forktex.com/open-source">Open source</a> ·
  <a href="https://forktex.com/contact">Contact</a>
</p>

---

FORKTEX S.R.L. builds backends, data pipelines, AI integrations and the infrastructure they
run on, and operates them in production. The same team runs four platforms of its own and
publishes the Python libraries those platforms are built on.

## Platforms

| | Platform | What it is | Status |
|---|---|---|---|
| <img src="https://forktex.com/forktex-assets/products/cloud-icon.svg" width="28"> | [**ForkTex Cloud**](https://forktex.com/products/cloud) | Declarative deployment. One `forktex.json` manifest becomes a local Docker Compose stack and an Ansible-managed VPS deployment: blue/green slots, automatic DNS, Let's Encrypt certificates. | Live — [cloud.forktex.com](https://cloud.forktex.com) |
| <img src="https://forktex.com/forktex-assets/products/network-icon.svg" width="28"> | [**ForkTex NetWork**](https://forktex.com/products/network) | Social and collaboration network for people and companies: profiles, a feed, connections, messaging, company pages and channels. Web, iOS and Android from one Expo client. | Live — [network.forktex.com](https://network.forktex.com) |
| <img src="https://forktex.com/forktex-assets/products/ai-icon.svg" width="28"> | [**ForkTex AI**](https://forktex.com/products/ai) | Capability-first AI platform: chat with structured output, embeddings, document extraction, transcription, retrieval and an MCP surface, behind one typed API. | Coming soon — [early access](https://forktex.com/contact) |
| <img src="https://forktex.com/forktex-assets/products/erp-icon.svg" width="28"> | [**ForkTex ERP**](https://forktex.com/products/erp) | Multi-tenant business platform: identity and access, parties, invoices with a lifecycle, ingestion and campaigns. One API, one client for Android, iOS and the web. | Coming soon |

The platform repositories are private.

## Open source

Python libraries, each one repository and one PyPI distribution. Every library depends on
`forktex`, the shared substrate. Licensed AGPL-3.0-or-later, or commercially from FORKTEX S.R.L.

| Library | What it does | |
|---|---|---|
| [**forktex**](https://github.com/forktex/forktex-py) | The substrate: logging, errors, typed models, PostgreSQL, Redis, S3 and a FastAPI app factory. | [![PyPI](https://img.shields.io/pypi/v/forktex.svg?label=)](https://pypi.org/project/forktex/) |
| [**forktex-fsd**](https://github.com/forktex/forktex-fsd) | The ForkTex Standard of Delivery: atoms in tracks, bound per repository in `fsd.toml`, checked and run by one tool. | [![PyPI](https://img.shields.io/pypi/v/forktex-fsd.svg?label=)](https://pypi.org/project/forktex-fsd/) |
| [**forktex-flow**](https://github.com/forktex/forktex-flow) | Durable workflows that run entirely on PostgreSQL. | [![PyPI](https://img.shields.io/pypi/v/forktex-flow.svg?label=)](https://pypi.org/project/forktex-flow/) |
| [**forktex-grid**](https://github.com/forktex/forktex-grid) | Tables, columns and rows declared at runtime, stored in PostgreSQL. | [![PyPI](https://img.shields.io/pypi/v/forktex-grid.svg?label=)](https://pypi.org/project/forktex-grid/) |
| [**forktex-mail**](https://github.com/forktex/forktex-mail) | Send and receive e-mail from any Python process: SMTP to send, IMAP to read. | [![PyPI](https://img.shields.io/pypi/v/forktex-mail.svg?label=)](https://pypi.org/project/forktex-mail/) |
| [**forktex-data**](https://github.com/forktex/forktex-data) | Typed records as one in-memory graph, searched by retrieval pipelines. | [![PyPI](https://img.shields.io/pypi/v/forktex-data.svg?label=)](https://pypi.org/project/forktex-data/) |
| [**forktex-documents**](https://github.com/forktex/forktex-documents) | Documents from structured data, rendered to HTML and PDF. | [![PyPI](https://img.shields.io/pypi/v/forktex-documents.svg?label=)](https://pypi.org/project/forktex-documents/) |
| [**forktex-crawl**](https://github.com/forktex/forktex-crawl) | Harvest public APIs politely, with a coverage report of what was reached. | [![PyPI](https://img.shields.io/pypi/v/forktex-crawl.svg?label=)](https://pypi.org/project/forktex-crawl/) |

```bash
pip install forktex          # the substrate
uv tool install forktex-fsd  # the delivery tool
```

Each library page on [forktex.com/open-source](https://forktex.com/open-source) carries the
same facts as its README.

## Services

- [**Software Development**](https://forktex.com/services/software-development) — backend, frontend, infrastructure and operations owned by one senior team, from first commit to production monitoring.
- [**Technology Consultancy**](https://forktex.com/services/technology-consultancy) — architecture reviews, technology strategy and modernisation plans, from a team that also operates systems.
- [**Business Automation**](https://forktex.com/services/business-automation) — document pipelines, registry verification and durable workflows.
- [**AI Integration**](https://forktex.com/services/artificial-intelligence) — retrieval with vector search, structured extraction, and an evaluation harness that measures accuracy.
- [**Sovereign Cloud**](https://forktex.com/services/sovereign-cloud) — declarative deployments on European infrastructure, with blue-green releases, managed DNS and TLS, and encrypted secrets.

[Case studies](https://forktex.com/insights) are on the website.

## How we work

- The API schema generates every client, so a contract change reaches consumers as a compile error.
- Database tests run against a real database, not a mock.
- Every repository starts with one command and passes the same gate: `fsd assurance`, `fsd security`, `fsd documentation`.
- Hourly work analytics, with an activity description on every entry, in every engagement.

Technologies: Python, FastAPI, Pydantic, SQLAlchemy, PostgreSQL, Redis, TypeScript, Next.js, React Native, Expo, Docker, Ansible, Terraform

## Contact

[info@forktex.com](mailto:info@forktex.com) · [Book a call](https://calendly.com/forktex) · [LinkedIn](https://www.linkedin.com/company/forktex)

Security issues in a library: see that repository's `SECURITY.md`.

<sub>FORKTEX S.R.L. · Bucharest, Romania</sub>
