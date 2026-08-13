# Subtitle Translation prompts

These prompts are intended for the configurable local prompt files used by
`The-Bazzar/Subtitle-translation`:

- `translate_prompt.md`: first-pass translation policy
- `proofread_prompt.md`: editor-only proofreading policy

Copy the selected files into a local Subtitle-translation checkout. They are
kept here instead of changing that project's `.example` configuration files.

The proofreading prompt permits broad target-language restructuring when it
improves the translation, but source-language changes remain limited to local,
evidence-supported ASR corrections enforced by the pipeline safety gate.
