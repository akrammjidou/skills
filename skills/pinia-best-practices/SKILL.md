---
name: pinia-best-practices
description: Pinia store TypeScript configuration and typing issues. Covers storeToRefs type loss, getters circular references, and setup store patterns. Use when working with Pinia stores in Vue 3 projects, debugging store type errors, or fixing storeToRefs type inference.
license: MIT
metadata:
  author: hyf0
  version: "1.0.0"
---

# Pinia Best Practices

TypeScript configuration and common pitfalls for Pinia stores in Vue 3 applications.

## When to Apply

- Working with Pinia stores in TypeScript projects
- Debugging `storeToRefs` type issues
- Fixing getter circular type references
- Setting up type-safe store patterns

## Rules

| Rule | Impact | Description |
|------|--------|-------------|
| [storeToRefs-type-loss](rules/storeToRefs-type-loss.md) | HIGH | Fix incorrect nested ref types with Vue 3.5+ |
| [getters-circular-types](rules/getters-circular-types.md) | MEDIUM | Fix TypeScript `any` or circular errors in getters using `this` |

## Reference

- [Pinia Documentation](https://pinia.vuejs.org/)
- [Pinia TypeScript Guide](https://pinia.vuejs.org/core-concepts/#typescript)
