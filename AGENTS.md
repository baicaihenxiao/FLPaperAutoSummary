# AGENTS.md

## Paper Summary Table Conventions

The following rules apply when generating or revising the federated learning
paper summary tables (for example, the Markdown files under `2025/`).


### `CCF` column

- Use only `A`, `B`, or `C` as the cell value, matching the paper venue's CCF
  rank. Do not write the full label (e.g., do not write `CCF A`).

### `Title & Abstract` column

- Format the paper title as inline code, for example `` `Privacy-Preserving
  Federated Learning` ``, rather than plain text.
- The content in the `Abstract` column is the abstract of the paper, copied
  verbatim from the paper's own abstract text.
- Fill the cell with the format `` `Title` - Abstract ``.


### `Venue` column

- Use the short venue abbreviation only, for example `TIFS`, not the full
  publisher-prefixed form (e.g., do not write `IEEE TIFS`).

### `URL` column

- Prefer the DOI URL format, for example
  `https://doi.org/10.1109/TIFS.2024.3484946`.
- Use this canonical DOI form rather than publisher landing-page or DBLP links
  whenever a DOI is available.
- Use `[➡️](url)` Markdown link format instead of plain DOI URL strings

### `added date` column

- Use the date when the line is added to the table
- The format is `MM/YYYY`, eg, `06/2026`

## Searching for Paper Info

- When searching for paper info, you may fetch the venue URLs listed in
  `ccf.md`. That file is the CCF recommended catalog of international
  conferences and journals, organized by field and rank (A/B/C), and each entry
  provides the venue abbreviation, full name, publisher, and an address URL
  (usually a DBLP listing).
- Use these URLs to look up a venue's DBLP page (to locate or verify a paper's
  title, authors, year, and DOI) and to confirm the venue's CCF rank.

## Summary Navigation

- When adding a Markdown file, also update `SUMMARY.md` so the navigation list
  includes the new file.
- Match the nested hyphen indentation in `SUMMARY.md` to the Markdown file's
  location, for example year, then venue, then the file link.
