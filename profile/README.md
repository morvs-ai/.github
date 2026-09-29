<p align="center">
  <img src="https://morvs.ai/logo-512.png" width="88" alt="MORVS mark">
</p>

<h1 align="center">MORVS</h1>
<p align="center"><strong>Private intelligence infrastructure.</strong></p>

MORVS builds systems for AI data, privacy, and verifiable public information. It is the public brand of AI Analytics LLC.

### Public data API

Explore the [dataset catalog](https://api.morvs.ai/datasets/), [OpenAPI specification](https://api.morvs.ai/openapi.json), [freshness report](https://api.morvs.ai/api/v1/freshness), and [source terms](https://api.morvs.ai/license).

A quick start with two public endpoints:

```bash
curl --fail --silent 'https://api.morvs.ai/api/v1/fda/recalls/recent?limit=1'
curl --fail --silent 'https://api.morvs.ai/api/v1/cisa/kev/recent?limit=1'
```

The API brings together records from sources with different rights and update schedules. Public access does not grant a blanket reuse license. Check each dataset's provenance and terms. When citing a record, include its API URL, retrieval date, and primary source.

[Website](https://morvs.ai/) · [Voidly](https://morvs.ai/voidly/) · [Research and writing](https://morvs.ai/writing/) · [Contact](https://morvs.ai/contact/)
