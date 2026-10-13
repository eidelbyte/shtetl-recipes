# shtetl recipes

The configuration root of shtetl (zconfig, planning.md 4.4), as
upstream ships it: `shtetl bootstrap --recipes <url>` clones it into
the config root.

- `shtetl.conf`: the site's settings and the default of every recipe.
- `foundations/`, `containers/`, `systems/`: recipes, a file each.
  Upstream ships none yet.

This is its own repository, split out of shtetl's tree with its
history (github.com/eidelbyte/shtetl, where it began as
shtetl-recipes/). shtetl's planning.md, 4.4 and 5.4, says what it is
for and how a site keeps its own files in it.
