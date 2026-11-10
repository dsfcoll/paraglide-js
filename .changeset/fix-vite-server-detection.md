---
"@inlang/paraglide-js": patch
---

Preserve Vite's SSR detection expression when resolving compiler defaults, while respecting explicit plugin and config overrides. Keep the generated `isServer` declaration typed as `boolean` for the Vite expression.
