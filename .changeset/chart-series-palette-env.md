---
'@hyperdx/app': minor
---

feat: set `NEXT_PUBLIC_CHART_SERIES_PALETTE` to a comma-separated list of hex
colors (e.g. `#3ca951,#a463f2,#6cc5b0`) to replace the colors chart series take,
in order. Unset keeps the default palette; invalid entries are ignored with a
console warning. Colors picked by name on number and table tiles are unchanged.
