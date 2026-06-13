# Kyoto Encyclopedia of Genes and Genomes (KEGG)

KEGG is an integrated database resource for understanding high-level functions and utilities of biological systems from molecular-level information derived from genome sequencing and high-throughput experiments.

The KEGG REST API at [rest.kegg.jp](https://rest.kegg.jp) provides programmatic access to databases covering biological pathways, metabolic networks, molecular interactions, drug targets, disease associations, chemical compounds, genomic sequences, and functional orthologs across thousands of organisms.

## API Operations

| Operation | Description |
|-----------|-------------|
| `info`    | Display database release information and statistics |
| `list`    | Obtain entry identifiers and associated names |
| `find`    | Search entries by keyword, formula, molecular weight, or sequence |
| `get`     | Retrieve full database entries (flat-file, KGML, JSON, image, sequence) |
| `conv`    | Convert identifiers between KEGG and external databases |
| `link`    | Find related entries through cross-database references |
| `ddi`     | Query adverse drug-drug interactions |

## Base URL

```
https://rest.kegg.jp/<operation>/<argument>[/<argument2>...]
```

## Key Databases

- **KEGG PATHWAY** — Biological pathway maps
- **KEGG BRITE** — Hierarchical classification systems
- **KEGG MODULE** — Functional pathway units
- **KEGG KO** — KEGG Orthology (functional orthologs)
- **KEGG GENES / GENOME** — Genes and genomic sequences
- **KEGG COMPOUND / GLYCAN / REACTION / ENZYME** — Chemical and biochemical data
- **KEGG DISEASE / DRUG / NETWORK** — Health and pharmacological data

## Access & Licensing

- **Academic REST API** — Free, no API key required, 3 requests/second limit
- **FTP Academic Subscription** — ~$2,000–$5,000/year via NPO Bioinformatics Japan / Pathway Solutions
- **Commercial License** — Available through [Pathway Solutions](https://www.pathway.jp/en/licensing.html)

## Resources

- [KEGG REST API Documentation](https://www.kegg.jp/kegg/rest/keggapi.html)
- [KEGG Legal / Terms of Use](https://www.kegg.jp/kegg/legal.html)
- [Pathway Solutions Commercial Licensing](https://www.pathway.jp/en/licensing.html)
- [Academic FTP Subscription](https://www.pathway.jp/en/academic.html)
