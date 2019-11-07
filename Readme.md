
# Reproducible Shiny apps with shinymeta

### Event

Nov 11, 2019<br/>
Autumn Biostatistics Annual Conference US (ABACUS)<br/>
GlaxoSmithKline<br/>
Phoenixville, PA

### Abstract

Shiny makes it easy to take domain logic from an existing R script and wrap some reactive logic around it to produce an interactive webpage where others can quickly explore different variables, parameter values, models/algorithms, etc. Although the interactivity is great for many reasons, once an interesting result is found, it’s more difficult to prove the correctness of the result since: (1) the result can only be (easily) reproduced via the Shiny app and (2) the relevant domain logic which produced the result is obscured by Shiny’s reactive logic. The R package shinymeta provides tools for capturing and exporting domain logic for execution outside of a Shiny runtime (so that others can reproduce Shiny-based result(s) from a new R session).