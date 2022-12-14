# hugo-img-comparison

Shortcode to add the `img-comparison-slider` library and frame in Hugo documents

# Usage

1. Add the repository as a submodule

```
git submodule add https://github.com/ericswpark/hugo-img-comparison.git themes/hugo-img-comparison
```

2. Add `hugo-img-comparison` as a theme in your `config.toml`:

```
theme = ["hugo-img-comparison", "default-theme-name"]
```

3. Add the following snippet where you want to embed image comparison sliders:

```
{{< imgcmp left="left.png" right="right.png" >}}
```

