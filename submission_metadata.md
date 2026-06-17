# Submission metadata

## Title

Intervention-Based Movability Representations in Minimalist Embodied Predictive Agents

## Author

Yugen

## Recommended venue path

- First public preprint: arXiv
- Primary arXiv category: `cs.AI`
- Possible cross-list: `cs.LG`

## Suggested arXiv comments

21 pages, 1 figure, 11 tables. Technical report / preprint.

## Suggested license

Use the standard arXiv non-exclusive license unless a target journal requires a different preprint license.

## Abstract

Physical understanding in embodied agents requires more than predicting regular motion in pixels. This paper studies a deliberately narrow case: whether a small predictive agent can learn a representation of movability, the difference between objects that change under pushing and boundaries that do not. In a 2D world, agents learn by predicting the next observation from the current observation and action. A vector causal perturbation framework (CPF) then probes the learned hidden states. The main positive result is limited but stable: an agent with only eight distance sensors separates movable and immovable contexts, and in causal-swap tests the representation follows intervention outcome rather than object appearance. Blind generalization, pre-contact rollouts, and CPF sensitivity checks support the same interpretation. The boundary is equally important. The representation depends on temporal continuity, degrades under noise, and collapses when vision supplies appearance shortcuts. Additional baselines localize the failure: recurrence alone is not sufficient, ordinary supervised labels learn shortcuts, object-slot memory solves temporal breaks when object structure is provided, and supervised 2D or 3D pixel-effect models can recover intervention labels. The remaining hard case is raw counterintuitive vision, where the strongest tested visual slot baseline remains near chance. These results support a cautious claim: minimalist embodied prediction can produce movability-like representations under shortcut deprivation, but robust visual object-state learning and full generative counterfactual simulation remain unsolved.

## Upload files

- arXiv source zip: `submission/arxiv_source.zip`
- Reader PDF: `submission/paper_submission.pdf`
- Journal/backup package: `submission/journal_package.zip`

## Endorsement note

If arXiv requires endorsement, start the submission anyway, copy the generated endorsement request link/code, then use `paper/endorsement_email_template.md` to contact a small number of relevant eligible endorsers.
