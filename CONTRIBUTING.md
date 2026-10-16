# Contributing

Keep the skill focused on a small, evidence-backed referral shortlist and personalized drafts.

Useful changes include a reproducible failure case, clearer setup instructions, better treatment of uncertain evidence, or a verified report from another compatible agent host. Explain what input failed, the observed behavior, and the expected result.

Before submitting:

- Use fictional or thoroughly anonymized examples. Do not upload resumes, private messages, contact lists, account data, or browser credentials.
- Run the relevant cases in [evals/scenarios.md](evals/scenarios.md), especially missing evidence and approval boundaries.
- Check that README instructions and the [skill metadata](agents/openai.yaml) still match the workflow.
- Describe what you actually tested. Separate supplied-evidence behavior from live-browser behavior.

Changes must preserve explicit approval before contact, truthful claims about the candidate and recipients, and a bounded shortlist. Do not add bulk sending, scraping, guessed private email addresses, or follow-ups that run without a separate user request.

There is no build step or runtime dependency in this instruction-only package. Behavioral review and working installation instructions matter more than a badge suggesting otherwise.
