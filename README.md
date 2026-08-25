# Kulturskript-Werkstatt

A browser-based prototype of an AI-assisted annotation environment for developing
critical cultural awareness in second-language German (DaF).

Learners read short passages from national family-policy documents, select a stretch
of text, and answer three learner-facing questions — what is at stake, how the family
is pictured, and how the text makes its case. Every annotation must be justified in
the learner's own words. A feedback layer responds with a single question anchored in
the wording of the passage; it never names the correct option and never evaluates a
country or a policy.

## Status

Research prototype, built for a pre-classroom evaluation. In this build the feedback
layer is reproduced by rule (Wizard-of-Oz): it follows the study's prompt contract
exactly — no verdict, one piece of evidence, one question, capped length — but calls
no language model.

## Contents

- `index.html` — the complete environment, self-contained. Open it in any browser;
  no installation, account, or network connection required.

## Excerpts

The bundled excerpts are verbatim passages from four publicly available documents,
each cited in the interface with its page number. Country labels are metadata of the
text, not claims about people. Further passages can be loaded at runtime under
**Materials**; they stay in the viewer's own browser.

## Interface languages

German (default), Turkish, English.

## Funding

Anadolu University Scientific Research Projects Commission (BAP), SÇB-2026-3204.
