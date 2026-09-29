<p align="center">
  <img src="./assets/morvs-banner.png" alt="MORVS. Private intelligence infrastructure." width="100%">
</p>

<h1 align="center">Built beneath intelligence.</h1>

<p align="center">
  Source-aware data. Private systems. Control over what AI can see and do.
</p>

---

### The public surface

**The record.** A machine-readable index of public information with source links, freshness metadata, and dataset-specific terms. [Inspect the catalog](https://api.morvs.ai/datasets/) · [Read the API specification](https://api.morvs.ai/openapi.json)

**The receipt.** The [public API example](https://github.com/morvs-ai/public-api) records the exact response hash and reported dataset freshness at retrieval time. Inspect it, run it, and check the limits.

**The private layer.** [Voidly](https://morvs.ai/voidly/) connects our work in privacy, censorship measurement, and information access. Its public data is distinct from its private infrastructure.

**The network.** [Nexcom](https://morvs.ai/nexcom/) is our publication and distribution network. [Research and writing](https://morvs.ai/writing/) makes the methods and limits visible.

### Query the record

```bash
curl --fail --silent 'https://api.morvs.ai/api/v1/fda/recalls/recent?limit=1'
curl --fail --silent 'https://api.morvs.ai/api/v1/cisa/kev/recent?limit=1'
```

Use the [freshness report](https://api.morvs.ai/api/v1/freshness) and [source terms](https://api.morvs.ai/license) before interpreting or reusing a result. Public access does not grant a blanket license across every source. Cite the record URL, retrieval date, and primary source.

---

<p align="center">
  <a href="https://morvs.ai/">MORVS</a> &nbsp;·&nbsp;
  <a href="https://api.morvs.ai/datasets/">Data</a> &nbsp;·&nbsp;
  <a href="https://morvs.ai/voidly/">Voidly</a> &nbsp;·&nbsp;
  <a href="https://morvs.ai/nexcom/">Nexcom</a> &nbsp;·&nbsp;
  <a href="https://morvs.ai/contact/">Contact</a>
</p>

<p align="center"><sub>MORVS is the public brand of AI Analytics LLC.</sub></p>
