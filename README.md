# hugo-img-comparison

Shortcode to add the `img-comparison-slider` library and frame in Hugo documents

# Installation

## Hugo Module

1. Add the repository as a Hugo module

```
hugo mod get github.com/ericswpark/hugo-img-comparison
```

2. Add to your `config.toml`:

```toml
# Modules
[module]
  # Other module imports here...
  [[module.imports]]
    path = "github.com/ericswpark/hugo-img-comparison"
    disable = false
```

## Git Submodule (deprecated)

1. Add the repository as a submodule

```
git submodule add https://github.com/ericswpark/hugo-img-comparison.git themes/hugo-img-comparison
```

2. Add `hugo-img-comparison` as a theme in your `config.toml`:

```
theme = ["hugo-img-comparison", "default-theme-name"]
```

# Usage

Add the following snippet where you want to embed image comparison sliders:

```
{{< imgcmp left="left.png" right="right.png" >}}
```
