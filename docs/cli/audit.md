---
id: audit
title: pnpm audit
---

Added in: 4.3.0

Checks for known security issues with the installed packages.

## Options

### --audit-level &lt;severity>

* Type: **low**, **moderate**, **high**, **critical**
* Default: **low**

Only print advisories with severity greater than or equal to `<severity>`.

### --json

Output audit report in JSON format.

### --dev

Only audit dev dependencies.

### --prod

Only audit prod dependencies.
