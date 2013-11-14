Contributing
============
Thanks for adding a [Glean Contrib Source][source]!

[Pull Requests][pr] are always welcome.

Each Source is represented by a single [TOML][toml] document.

```toml
# iptccodes.toml
identifier = "simeonwillbanks/iptccodes"
name = "iptccodes"
description = "Metadata Taxonomies for News"
```

- `identifier` indicates the Source GitHub repository
- `name` and `description` are used by Glean search

```bash
$ glean search --contrib
iptccodes -- Metadata Taxonomies for News
```

[source]: https://github.com/glean/glean#sources
[pr]: https://help.github.com/articles/using-pull-requests
[toml]: https://github.com/mojombo/toml
