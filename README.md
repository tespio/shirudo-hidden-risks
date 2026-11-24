# The Hidden Risks of Shirudo

A visual, independent security review of **Shirudo**, the OpenAI × Cisco eBPF security platform announced 22–23 November 2026.

**Read it live:** https://tespio.github.io/shirudo-hidden-risks/

## What this is

Shirudo is an AI-fed, kernel-level enforcement layer for Linux. This page reads the project's own public documentation — the threat model, system requirements, interoperability notes and recovery guide — and lays out the deployment, availability, integrity and governance risks in plain language.

The argument is not that Shirudo is malware. It isn't. The argument is that it is a pre-release, fork-requiring, root-resistant system whose failure modes are unrecoverable, and that it is being aimed at exactly the organizations that cannot satisfy its prerequisites.

## Contents

| File | Purpose |
| --- | --- |
| `index.html` | The published page. Self-contained: inline CSS and JS, no build step, no trackers, no external images. |
| `the_hidden_risks_of_shirudo.md` | The source article. |
| `.nojekyll` | Tells GitHub Pages to serve the page as-is. |

## Notes

- Independent analysis. Not affiliated with, endorsed by, or sponsored by OpenAI or Cisco.
- "OpenAI", "Cisco", "Shirudo" and related marks belong to their respective owners.
- The geometric mark on the page is an original motif, not a company logo.
- Every claim about Shirudo's behavior is drawn from the project's public documentation, quoted or paraphrased, as of 24 November 2026.
