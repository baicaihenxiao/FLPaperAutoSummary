# FLPaperAutoSummary

> **Note for AI agents**: When searching this repository for paper information, **do not** use monthly update tables (e.g., `2026-06-updated-FL-ALL.md`). These tables are temporary snapshots accumulated during monthly maintenance and may contain duplicate or unverified entries. Instead, always use the per-venue summary tables under the year folders (e.g., `2025/`, `2026/`, etc.), such as `2026/TIFS/2026-TIFS-FL-ALL.md` or `2026/TIFS/2026-TIFS-FL-Star.md`. These folder-based tables are the canonical, deduplicated source of paper information.

<p class="check" markdown="1"> Use AI to fetch federated learning paper basic info from CCF A rank journals and conferences. </p> 

<p class="icon tips" markdown="1"> 重点关注以下 Venue：TIFS, TDSC, TMC, INFOCOM, WWW, TSC, USENIX Security. </p>

<p class="icon notice" markdown="1"> baicaiDocsStyle.css 中设置了倒数第 5 列的宽度，所以不要在后面插入新列。 </p>

# Instructions to update monthly table
```
Update only the current monthly FL update summary table in this repository.

Task:
- Find the latest relevant federated learning papers that are not already listed anywhere in the repository’s paper summary tables.
- Only consider papers published in these venues: TIFS, TDSC, TMC, INFOCOM, WWW, TSC, and USENIX Security.
- Update only the current monthly FL summary table.
- If the current month does not yet have a file, create a new monthly Markdown file using the same format as `2026-06-updated-FL-ALL.md` and update `SUMMARY.md` so the new file appears in navigation.
- Do not modify any other tables or files unless required for the monthly table update and the corresponding `SUMMARY.md` entry.

Runtime limit:
- Finish within 35 minutes.
- After 28 minutes, stop searching for additional papers and finalize only papers that are already fully verified.
- If no fully verified new paper is found before the limit, make no edits and report that no papers were added.
- Do not leave partial table edits, uncommitted changes, or unpushed commits.

Rules:
- Follow all conventions in `AGENTS.md`.
- Use only `A`, `B`, or `C` in the `CCF` column.
- Format `Title & Abstract` as `` `Title` - Abstract ``, with the abstract copied verbatim from the paper.
- Use only short venue abbreviations in the `Venue` column.
- Use `[➡️](https://doi.org/...)` for the `URL` column when a DOI is available.
- Format `added date` as `DD/MM/YYYY` for monthly tables.
- In `Change Log`, prepend `⭐ ` to the paper title only if the paper is starred. Do not change the list format.  The date should be 1st level list, the paper list should be 2nd level list.
- Do not add papers that already appear in this table or any other tables in the repository.
- Ensure there are no blank lines anywhere in the table after editing.

Workflow:
- Use the venue sources listed in `ccf.md` to verify paper titles, authors, venue, year, DOI, and CCF rank.
- Prefer DOI URLs over publisher landing pages when available.
- If no suitable new papers are found, make no unnecessary edits and report no changes clearly in `Change Log`.

Deliverables:
- Summarize every file changed.
- Summarize every paper added.
- If no papers were added, state that explicitly.
- Commit and push the changes to the `main` branch after finishing.
```

## Project URL

> * <https://baicaihenxiao.github.io/FLPaperAutoSummary/>
> * <https://fl.cser.site/>


## AboutMe
> [GitHub](https://github.com/baicaihenxiao)

## Reference

> Powered by [**docsify**](https://docsify.js.org/#/)

## License

The content of this site is licensed under the [Creative Commons Attribution-NonCommercial-NoDerivs 3.0 Unported License](http://creativecommons.org/licenses/by-nc-nd/3.0/)

[![](https://i.creativecommons.org/l/by-nc-nd/3.0/88x31.png)](http://creativecommons.org/licenses/by-nc-nd/3.0/)

