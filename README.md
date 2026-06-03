# pipeline-templates — moved

This repository was transferred to **[romaine-life/pipeline-templates](https://github.com/romaine-life/pipeline-templates)**.

`nelsong6/pipeline-templates` is now a **retired placeholder**. It intentionally contains **no reusable workflows**, so any lingering reference such as:

```yaml
uses: nelsong6/pipeline-templates/.github/workflows/<name>@main
```

will **fail fast** ("workflow file not found") instead of silently resolving through GitHub's old transfer redirect — which creating this placeholder retires.

Update any such reference to:

```yaml
uses: romaine-life/pipeline-templates/.github/workflows/<name>@main
```

_Part of the nelsong6 → romaine-life org migration (Phase 4)._
