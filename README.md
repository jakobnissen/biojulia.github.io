# BioJulia.dev

[![Website URL badge](https://img.shields.io/badge/site-BioJulia.dev-blue)](https://biojulia.dev)



## Static Site Tech

Using [Xranklin](https://github.com/tlienart/Xranklin.jl) under the hood.

### Celeste Template

Based on the wonderful [Celeste](https://github.com/nicoelayda/celeste) by @nicoelayda.

#### Development

Any changes to the CSS should be made to the SCSS files in `_sass/` and compiled using `Sass.jl` as follows:

```julia
Sass.compile_file("style.scss", "../_css/celeste.min.css"; output_style = Sass.compressed)
```

All the `Franklin.jl` related changes are in `_sass/adjust.scss`
