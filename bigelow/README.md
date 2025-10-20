# Bigelow Collection

> **Note:** This README was drafted from a neutral template because the Arches page (https://arches.union.edu/bigelow) was not accessible from my environment. Replace the sections marked **[UPDATE FROM ARCHES]** with the official text from the collection description.

## Overview
**[UPDATE FROM ARCHES]** Provide a short paragraph describing the Bigelow collection: what it contains, its historical/academic significance, date ranges, and primary formats (e.g., images, documents, audio).

## Source & Provenance
- **Institution:** Schaffer Library, Union College
- **Collection Name:** Bigelow
- **Source System:** Arches
- **Persistent URL:** https://arches.union.edu/bigelow  (copy any canonical IDs or permalinks here)

## Data Files
- `8-68f6550c847ac.csv` — CSV export of collection metadata (cleaned to remove empty columns).  
  - Delimiter: `,`
  - Encoding: UTF-8
  - Header row included: Yes
  - Line endings: LF/CRLF (platform-dependent)

## Field Notes
Describe key fields present in the CSV and how to interpret them. For example:  
- `title` — item title or formal name.  
- `creator` — person or entity responsible.  
- `date` — normalized date or textual date.  
- `identifier` — local system identifier or call number.  
- `subjects_*` — controlled vocabularies or topical terms.  
**[UPDATE FROM ARCHES]** Replace with the exact fields present and their meanings.

## Cleaning Steps
- Removed columns that were completely empty across all rows.
- Optionally removed columns that were invariant (same value in every row) if requested.  
Include your exact cleaning script/command for reproducibility (see below).

## Reproducibility
```python
import pandas as pd

df = pd.read_csv("8-68f6550c847ac.csv")
df = pd.read_csv("8-68f6550c847ac.csv")
df = df.dropna(axis=1, how="all")
df.to_csv("8-68f6550c847ac_clean.csv", index=False)
```
If there were additional drops, list them explicitly.

## Rights & Usage
**[UPDATE FROM ARCHES]** Add rights statement, license (if any), and any reuse requirements.

## Contacts
- **Collection Contact:** **[UPDATE FROM ARCHES]** (name/email)
- **Repository:** Schaffer Library, Union College
