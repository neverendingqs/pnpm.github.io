---
id: why
title: pnpm why
---

Shows the packages that depend on &lt;pkg>

## Synopsis

```text
pnpm why [-r] [--filter &lt;package selector>]
         [&lt;package pattern> ...]

pnpm recursive why [--filter &lt;package selector>]
                   [&lt;package pattern> ...]
```

## Options

### --recursive, -r

Perform command on every package in subdirectories
or on every workspace package, when executed inside a workspace.

### --json

Added in: 3.7.0

Show information in JSON format.

### --long

Show extended information.

### --parseable

Show parseable output instead of tree view.

### --global

List packages in the global install directory instead of in the current project.

### --prod, --production, --only prod

Display only the dependency tree for packages in `dependencies`.

### --dev, --only dev

Display only the dependency tree for packages in `devDependencies`.

### --filter &lt;package_selector>

[Read more about filtering.](../filtering)
