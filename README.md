# Syntelligo

Syntelligo builds language-first knowledge tools. We combine multilingual lexical data, graph databases, and clean web UX so developers can **understand words, meanings, and relations**—and ship smarter NLP features faster.

## What we do
- **Multilingual semantics:** definitions, synonyms/antonyms, word senses, and cross-lingual mappings.
- **Graph-native APIs:** simple traversal of relations for discovery and tagging.
- **Practical tooling:** import/export scripts, schema examples, and lightweight ontologies.

## Spotlight: SDO — Syntelligo Domain Ontology
**SDO** is a lightweight domain taxonomy for tagging words, documents, and datasets. It favors clarity over complexity:

- **Shallow hierarchy (depth 1–3)** for reliable roll-up and drill-down  
- **Multilingual labels** (e.g., `en`, `nob`) for direct UI display  
- **Interoperable formats:** canonical **JSON**, plus optional **CSV** and **SKOS/Turtle**  
- **Graph-friendly:** only `HAS_CHILD` edges between domain nodes; easy imports to Memgraph/Neo4j

The SDO will be published as a separate repository in this organization (e.g., `sdo-ontology`) with:
- The canonical `sdo.json`
- Import snippets (Cypher) and validation queries
- Format variants (CSV, SKOS) and a small demo page

---

## Links
- 🌐 Website: **https://syntelligo.com**
- 🧭 Browse the org’s repositories for SDO and related tooling
- 💬 Issues and pull requests are welcome—brief rationale and examples help us review quickly
