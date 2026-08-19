# Case Studies

Full requirement-to-production write-ups of real ML/AI systems, following
the same
[`_TEMPLATE.md`](https://github.com/abhibatsa/architecting-software/blob/main/01-system-design-and-architecture/04-real-world-case-studies/_TEMPLATE.md)
used in the flagship repo.

## Checklist

- [ ] `resume-scoring-pipeline-with-llm-judges.md` — concurrent batch
      scoring, prompt design for consistency across candidates, handling
      LLM judge variance
- [ ] `brand-impersonation-threat-detection-system.md` — real-time
      analysis pipeline, false-positive/false-negative trade-offs at scale
- [ ] `ai-test-generation-from-requirements.md` — multi-tenant SaaS,
      usage metering, and the gap between "generates a plausible test" and
      "generates a test that actually catches regressions"
- [ ] `generative-content-pipeline-at-scale.md` — structured prompt →
      structured output → paid-content-gating architecture

## Note on framing

Company names are intentionally omitted per the same convention used in
the flagship repo's leadership stories — frame as "a resume-screening
product," "a brand-protection platform," etc. The architecture and the
lessons are the content; the employer isn't.
