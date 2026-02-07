# POINTERS — Code Crunchers Technologies

default_branch: main
repo: https://github.com/<OWNER>/code-crunchers-technologies

## How Voxia should resolve “open/display <file>”
- HTML needs `source_mirror` to guarantee verbatim source display.
- CSS/JS/MD can usually use `raw_url`.

## Current (exists today)

- id: readme
  runtime: README.md
  raw_url: https://raw.githubusercontent.com/<OWNER>/code-crunchers-technologies/main/README.md

## Future site (enable when these files exist)

# - id: site_home
#   runtime: index.html
#   source_mirror: source/index.html.txt
#   raw_url: https://raw.githubusercontent.com/<OWNER>/code-crunchers-technologies/main/index.html
#
# - id: site_theme
#   runtime: theme.css
#   source_mirror: source/theme.css.txt
#   raw_url: https://raw.githubusercontent.com/<OWNER>/code-crunchers-technologies/main/theme.css

## Notes
- `source/` is reserved for chat-safe mirrors.
- When you create `index.html`, immediately copy it to `source/index.html.txt`.
