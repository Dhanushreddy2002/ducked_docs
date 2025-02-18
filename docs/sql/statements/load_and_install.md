---
layout: docu
title: LOAD / INSTALL Statements
railroad: statements/load_and_install.js
---

## `INSTALL`

The `INSTALL` statement downloads an extension so it can be loaded into a DuckDB session.

### Examples

Install the [`httpfs`]({% link docs/extensions/httpfs/overview.md %}) extension:

```sql
INSTALL httpfs;
```

Install the [`h3` Community Extension]({% link community_extensions/extensions/h3.md %}):

```sql
INSTALL h3 FROM community;
```

### Syntax

<div id="rrdiagram2"></div>

## `LOAD`

The `LOAD` statement loads an installed DuckDB extension into the current session.

### Examples

Load the [`httpfs`]({% link docs/extensions/httpfs/overview.md %}) extension:

```sql
LOAD httpfs;
```

Load the [`spatial`]({% link docs/extensions/spatial/overview.md %}) extension:

```sql
LOAD spatial;
```

### Syntax

<div id="rrdiagram1"></div>
