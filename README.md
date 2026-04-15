# ziniao-official-sites

Official site presets for [ziniao](https://github.com/tianyehedashu/ziniao) — JSON templates for automated web data fetching.

## Directory layout

```
<site>/<action>.json
```

Each JSON file is a preset template. Example: `rakuten/rpp-search.json`.

## Usage

```bash
# Add this repo
ziniao site add https://github.com/tianyehedashu/ziniao-official-sites.git

# List available presets
ziniao site list

# Update
ziniao site update ziniao-official-sites
```
