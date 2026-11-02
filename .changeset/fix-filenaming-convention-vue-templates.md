---
"@biomejs/biome": patch
---

Fixed [#12818](https://github.com/biomejs/biome/issues/12818): [`useFilenamingConvention`](https://biomejs.dev/linter/rules/use-filenaming-convention/) no longer reports a Vue, Svelte, or Astro file once per template expression when `html.experimentalFullSupportEnabled` is enabled.
