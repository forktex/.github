<p align="center">
  <a href="https://forktex.com"><img src="https://raw.githubusercontent.com/forktex/.github/master/profile/assets/forktex-icon.svg" width="88" alt="FORKTEX"></a>
</p>

<h1 align="center">FORKTEX</h1>

<p align="center">
  <b>We build software that ships.</b><br>
  Software engineering firm, Bucharest · Europe and North America since 2021<br>
  <a href="https://forktex.com"><b>forktex.com</b></a>
</p>

### Platforms

<div align="center">
<table>
  <tr>
    <td align="center" width="50%">
      <a href="https://forktex.com/products/cloud"><img src="https://raw.githubusercontent.com/forktex/.github/master/profile/assets/cloud-icon.svg" width="56" alt=""><br><b>ForkTex Cloud</b></a>
      <p>A declarative deployment platform. One <code>forktex.json</code> manifest becomes a local Docker Compose stack for development and an Ansible-managed VPS deployment in production, with blue/green slots, automatic DNS and Let's Encrypt certificates. Driven by a FastAPI controller and a typed Python SDK.</p>
      <a href="https://cloud.forktex.com">cloud.forktex.com ↗</a>
    </td>
    <td align="center" width="50%">
      <a href="https://forktex.com/products/network"><img src="https://raw.githubusercontent.com/forktex/.github/master/profile/assets/network-icon.svg" width="56" alt=""><br><b>ForkTex NetWork</b></a>
      <p>A social and collaboration network for people and companies: profiles, a feed, connections and messaging. Companies get a public page, channels where members talk, a contact inbox and partnerships, with roles and permissions. Web, iOS and Android from one client.</p>
      <a href="https://network.forktex.com">network.forktex.com ↗</a>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <a href="https://forktex.com/products/ai"><img src="https://raw.githubusercontent.com/forktex/.github/master/profile/assets/ai-icon.svg" width="56" alt=""><br><b>ForkTex AI</b></a>
      <p>A capability-first AI platform: chat with streaming and structured output, embeddings, document extraction, audio and video transcription, knowledge and retrieval, and an MCP surface, behind one typed API with a Python SDK. The capability is named, not the vendor.</p>
      <b>Coming soon</b>
    </td>
    <td align="center" width="50%">
      <a href="https://forktex.com/products/erp"><img src="https://raw.githubusercontent.com/forktex/.github/master/profile/assets/erp-icon.svg" width="56" alt=""><br><b>ForkTex ERP</b></a>
      <p>A multi-tenant business platform on the <code>forktex</code> substrate, built layer by layer: identity and access, then parties, invoices with a lifecycle, ingestion and campaigns. Each organisation's data is kept apart. One API, one client for Android, iOS and the web.</p>
      <b>Coming soon</b>
    </td>
  </tr>
</table>
</div>

### Open source

Eight Python libraries, each on GitHub and PyPI. AGPL-3.0-or-later, or a commercial licence. All build on `forktex`.

<div align="center">
<table>
  <tr>
    <td align="center" width="50%">
      <a href="https://github.com/forktex/forktex-py"><img src="https://raw.githubusercontent.com/forktex/forktex-py/master/docs/assets/forktex-banner.png" height="56" alt="forktex"></a>
      <p>The shared Python substrate: structured logs with a trace id, one error hierarchy with stable codes, typed models, PostgreSQL, Redis, S3 and a FastAPI app factory.</p>
    </td>
    <td align="center" width="50%">
      <a href="https://github.com/forktex/forktex-fsd"><img src="https://raw.githubusercontent.com/forktex/forktex-fsd/master/docs/assets/fsd-banner.png" height="56" alt="forktex-fsd"></a>
      <p>The ForkTex Standard of Delivery, and the tool that checks it. A repository binds atoms such as <code>test</code>, <code>audit</code> and <code>publish</code> to its own commands in one <code>fsd.toml</code>.</p>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <a href="https://github.com/forktex/forktex-flow"><img src="https://raw.githubusercontent.com/forktex/forktex-flow/master/docs/assets/flow-banner.png" height="56" alt="forktex-flow"></a>
      <p>Durable workflows that run entirely on PostgreSQL: cron schedules with leader takeover, pauses for a person's approval, and LLM tool calls that survive a restart.</p>
    </td>
    <td align="center" width="50%">
      <a href="https://github.com/forktex/forktex-grid"><img src="https://raw.githubusercontent.com/forktex/forktex-grid/master/docs/assets/grid-banner.png" height="56" alt="forktex-grid"></a>
      <p>Tables declared as data by your tenants, users or agents: typed columns, links and indexes, with validated writes and one query language. No migration, no deploy, one schema in your own PostgreSQL.</p>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <a href="https://github.com/forktex/forktex-mail"><img src="https://raw.githubusercontent.com/forktex/forktex-mail/master/docs/assets/mail-banner.png" height="56" alt="forktex-mail"></a>
      <p>Send and receive e-mail from any Python process: SMTP to send, IMAP to read, failures classified from the protocol codes, bounces matched to the message that caused them.</p>
    </td>
    <td align="center" width="50%">
      <a href="https://github.com/forktex/forktex-data"><img src="https://raw.githubusercontent.com/forktex/forktex-data/master/docs/assets/data-banner.png" height="56" alt="forktex-data"></a>
      <p>Working memory for scripts and agents: typed records loaded into one immutable graph, searched and packed into a token budget by retrieval pipelines, published as one versioned file and served over MCP.</p>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <a href="https://github.com/forktex/forktex-documents"><img src="https://raw.githubusercontent.com/forktex/forktex-documents/master/docs/assets/documents-banner.png" height="56" alt="forktex-documents"></a>
      <p>Invoices, contracts and reports generated as HTML and PDF from one typed record: your own document types, typed blocks, your theme and your jurisdiction's formats, and PDFs ready to sign.</p>
    </td>
    <td align="center" width="50%">
      <a href="https://github.com/forktex/forktex-crawl"><img src="https://raw.githubusercontent.com/forktex/forktex-crawl/master/docs/assets/crawl-banner.png" height="56" alt="forktex-crawl"></a>
      <p>Harvest public APIs politely, and prove what was harvested: capped result sets are split until the server answers in full, and a coverage report names what was not reached.</p>
    </td>
  </tr>
</table>
</div>

### Reach out

<div align="center">
<table>
  <tr>
    <td align="center" width="50%"><a href="mailto:info@forktex.com"><img src="https://img.shields.io/badge/Email-write_to_us-4BAE4F?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a></td>
    <td align="center" width="50%"><a href="https://forktex.com"><img src="https://img.shields.io/badge/Website-forktex.com-44D62C?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website"></a></td>
  </tr>
</table>
</div>

### Social

<div align="center">
<table>
  <tr>
    <td align="center" width="50%"><a href="https://www.linkedin.com/company/forktex"><img src="https://img.shields.io/badge/LinkedIn-forktex-0A66C2?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0yMC40NDcgMjAuNDUyaC0zLjU1NHYtNS41NjljMC0xLjMyOC0uMDI3LTMuMDM3LTEuODUyLTMuMDM3LTEuODUzIDAtMi4xMzYgMS40NDUtMi4xMzYgMi45Mzl2NS42NjdIOS4zNTFWOWgzLjQxNHYxLjU2MWguMDQ2Yy40NzctLjkgMS42MzctMS44NSAzLjM3LTEuODUgMy42MDEgMCA0LjI2NyAyLjM3IDQuMjY3IDUuNDU1djYuMjg2ek01LjMzNyA3LjQzM2MtMS4xNDQgMC0yLjA2My0uOTI2LTIuMDYzLTIuMDY1IDAtMS4xMzguOTItMi4wNjMgMi4wNjMtMi4wNjMgMS4xNCAwIDIuMDY0LjkyNSAyLjA2NCAyLjA2MyAwIDEuMTM5LS45MjUgMi4wNjUtMi4wNjQgMi4wNjV6bTEuNzgyIDEzLjAxOUgzLjU1NVY5aDMuNTY0djExLjQ1MnpNMjIuMjI1IDBIMS43NzFDLjc5MiAwIDAgLjc3NCAwIDEuNzI5djIwLjU0MkMwIDIzLjIyNy43OTIgMjQgMS43NzEgMjRoMjAuNDUxQzIzLjIgMjQgMjQgMjMuMjI3IDI0IDIyLjI3MVYxLjcyOUMyNCAuNzc0IDIzLjIgMCAyMi4yMjIgMGguMDAzeiIvPjwvc3ZnPg%3D%3D" alt="LinkedIn"></a></td>
    <td align="center" width="50%"><a href="https://x.com/forktex"><img src="https://img.shields.io/badge/X-@forktex-000000?style=for-the-badge&logo=x&logoColor=white" alt="X"></a></td>
  </tr>
  <tr>
    <td align="center" width="50%"><a href="https://www.instagram.com/forktex/"><img src="https://img.shields.io/badge/Instagram-@forktex-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram"></a></td>
    <td align="center" width="50%"><a href="https://www.facebook.com/profile.php?id=61593364083833"><img src="https://img.shields.io/badge/Facebook-FORKTEX-0866FF?style=for-the-badge&logo=facebook&logoColor=white" alt="Facebook"></a></td>
  </tr>
</table>
</div>
