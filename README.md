# blockchain-law

A public research portal for **blockchain law** and **digital asset markets law**.

This repository began as an RSA 301-B reader and now serves as a broader legal knowledge hub that includes:

- Full text of **N.H. Rev. Stat. Ann. ch. 301-B** (New Hampshire DAO Act)
- Full text of the **GENIUS Act** (Pub. L. 119-27)
- Comparative state DAO law analysis
- Registry and decentralization compliance analysis
- Stablecoin and market-structure context

## Site architecture

Static multi-page site with no build step:

- `index.html` — portal + RSA 301-B landing page
- `genius.html` — federal GENIUS Act text
- `stable-tokens.html` — stablecoin / market analysis
- `decentralization.html` — decentralization measurement analysis
- `registry.html` — registry/compliance checklist
- `comparison.html` — cross-jurisdiction comparison

## Machine-readable and AI ingestion

- `sitemap.xml` — crawl entrypoint
- `enrichment.json` — section-level structured metadata for RSA 301-B
- `ai-ingestion.json` — repository-level ingestion manifest with canonical content index

## Contributing

Open an [issue](https://github.com/Oranburg/blockchain-law/issues) to:

- Report source-text or citation errors
- Suggest additional legal tracks (federal/state/international)
- Propose schema or ingestion improvements for research tooling

## License

Statutory text is public law. Site implementation is MIT licensed.

## Superseded (2026-06-20)
This repository is superseded by **digital-assets**. The full NH RSA 301-B statute and the digital-asset law hub now live at https://oranburg.law/digital-assets/ (statute at `#/nh-rsa-301b`), where they use the shared Oranburg design system. This repository is kept for reference and is slated for archiving on GitHub. See the wiki Decision-2026-06-20 page.
