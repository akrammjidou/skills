# vue-skills

Agent skills for Vue 3 development.

## Installation

```bash
npx add-skill hyf0/vue-skills
```

## Available Skills

### 1. vue-best-practices (35 rules)

Comprehensive Vue 3 development best practices, TypeScript configuration, tooling troubleshooting, testing patterns, and composition API gotchas.

**Categories:**
- **Type Checking** - vue-tsc strict templates, defineModel generics
- **Tooling & Configuration** - Volar 3.0, moduleResolution, unplugin conflicts
- **Vite Configuration** - Path aliases, runtime env, HMR SSR, duplicate plugins
- **Component Patterns** - useTemplateRef, defineExpose, provide/inject, deep watch
- **Vue Router** - Route meta types, scrollBehavior, dynamic routes, typed params
- **Testing Patterns** - Suspense, Teleport, Pinia/Router mocking
- **Composition API** - Reactive destructuring, ref unwrapping, watchEffect, cleanup
- **SFC Patterns** - Script setup, CSS v-bind
- **TypeScript Patterns** - Component type helpers, event typing

### 2. pinia-best-practices (2 rules)

Pinia store TypeScript configuration and typing issues.

- storeToRefs type loss with Vue 3.5+
- Getters circular type references

### 3. vueuse-best-practices (2 rules)

VueUse composable patterns and TypeScript integration.

- SSR compatibility
- Target element refs

## Methodology

Every skill in this repository is created through a rigorous, evidence-based process:

**1. Real-World Issue Collection**

Skills are sourced from actual developer pain points:
- GitHub Issues (vuejs/core, vuejs/language-tools, vitejs/vite-plugin-vue, vuejs/pinia, vuejs/router)
- Stack Overflow high-vote questions
- Reddit r/vuejs discussions
- GitHub Discussions

**2. Multi-Model Verification**

Each skill undergoes systematic testing:
- **Baseline test**: Verify the model fails to solve the problem *without* the skill
- **Skill test**: Confirm the model correctly solves the problem *with* the skill
- **Consistency test**: Run multiple times to ensure reliable behavior

**3. Model Tier Validation**

Skills are tested across model capabilities:

| Model | Without Skill | With Skill | Requirement |
|-------|--------------|------------|-------------|
| Haiku | Expected: Fail | Bonus: Pass | Optional |
| Sonnet | Verified: Fail | **Must: Pass** | **Minimum bar** |
| Opus | May pass | Should pass | Reference |

**Acceptance criteria**: Sonnet must consistently solve the problem with the skill installed.

This ensures skills provide genuine value—teaching AI what it doesn't already know, not duplicating existing knowledge.

## License

MIT
