# POINTERS — Code Crunchers Technologies

repo: https://github.com/pacaud/code-crunchers-technologies
default_branch: main

## Resolver rules (Voxia)
- To display code as plain text in chat, use `raw_mirror_url`
- `source/` is the chat-safe mirror folder

## Mirrors (chat-safe)

- id: site_home_mirror
  runtime: index.html
  source_mirror: source/index.html.txt
  raw_mirror_url: https://raw.githubusercontent.com/pacaud/code-crunchers-technologies/main/source/index.html.txt

- id: site_theme_mirror
  runtime: theme.css
  source_mirror: source/theme.css.txt
  raw_mirror_url: https://raw.githubusercontent.com/pacaud/code-crunchers-technologies/main/source/theme.css.txt

## Meta

- id: pointers
  runtime: POINTERS.md
  raw_url: https://raw.githubusercontent.com/pacaud/code-crunchers-technologies/main/POINTERS.md

- id: readme
  runtime: README.md
  raw_url: https://raw.githubusercontent.com/pacaud/code-crunchers-technologies/main/README.md
