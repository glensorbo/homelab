---
id: search_and_replace
aliases:
  - vim
tags:
  - nvim
---

# nvim search and replace

## Search and replace project wide

```vim
:Ggrep <search-term>
```

```vim
:cfdo %s/<search-term>/<replace-term>/gc
```

```vim
:cfdo update
```

> [!NOTE]
> Ggrep (grep only git files) will find all places where `<search-term>` is <br /> `cfdo %s` will replace them and `cfdo update` will save all files
