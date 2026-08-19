# Prompt Engineering

Production prompting patterns — not "10 magic prompts," which is most of
what exists on this topic already and ages badly as models change.

## Checklist

- [ ] `prompt-structure-that-survives-model-upgrades.md` — patterns robust
      to swapping the underlying model, vs prompts hand-tuned to one
      model's quirks
- [ ] `few-shot-vs-zero-shot-when-each-wins.md`
- [ ] `structured-output-and-schema-enforcement.md`
- [ ] `prompt-injection-and-why-it-cant-be-fully-prompted-away.md` —
      directly reusable from GuardProbe's threat model
- [ ] `versioning-and-testing-prompts-like-code.md` — treating prompts as
      an artifact with regression tests, not throwaway strings
