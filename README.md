# Berlin LOD Basetheme

This repository contains a base set of Jinja templates for websites generated from linked open data from Berlin's public administration.

## Extra Variables

In `config.yml`, you can define an `extras` variable `global_stylesheets` with links to stylesheets. Those will be loaded in [base.html.jinja](/berlin/lod/basetheme/templates/base.html.jinja).

```yaml
extras:
  global_stylesheets:
    - "assets/css/bo_style.css"
```

## License

All code in this repository is published under the [MIT License](License).
