# docx-preview.yazi

Use [docx2txt](https://docx2txt.sourceforge.net/) to preview DOCX files in [yazi](https://github.com/sxyazi/yazi).

## Requirements

- [docx2txt](https://docx2txt.sourceforge.net/) - It's probably available in your package manager.
- yazi version 0.4

## Installation

Install with:

```sh
ya pack -a lpanebr/yazi-plugins:docx-preview
```

and enable by adding it to your `yazi.toml` config file:

```toml
[plugin]
prepend_previewers = [
    { name = "*.docx", run = "docx-preview" },
]
```

## Disclaimers

- This plugin was derived from [miller.yazi](https://github.com/Reledia/miller.yazi).
- Tested only with yazi version 0.4.3
