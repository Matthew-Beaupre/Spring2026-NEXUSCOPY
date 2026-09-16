# Held-out syllabus sourcing note — Sprint 2

- **Source pool:** Public university syllabus pages/documents, primarily UTEP and UNT Dallas, plus one UTEP/UNT Dallas government syllabus document.
- **Candidates screened:** 13 documents.
- **Rejected as duplicates:** 0.
- **Borderline/review candidates:** 2 (the two Wong anthropology syllabi); they were not placed in `heldout_candidates/` because `corpus_dedup.py` classified them as REVIEW against each other.
- **Accepted candidates:** 11. Ten were selected for the held-out set; one accepted candidate (the psychology syllabus) was kept out of the set as a reserve.
- **Selected held-out set:** 10 documents, all ACCEPTed by `corpus_dedup.py screen`.

## Remaining Sprint 2 sourcing plan

The remaining ~70 documents will be sourced in batches from additional university departments and official syllabus repositories, prioritizing departments that have little or no representation in the two existing corpora. Each new candidate will be screened with `corpus_dedup.py` before it is added. Candidates that are REJECTed will be discarded as duplicates; REVIEW results will be checked manually and kept out of the held-out set unless confirmed as genuinely distinct. The goal is to continue collecting enough fresh candidates to reach roughly 70 additional documents while keeping the held-out set separate from both existing corpora and all ground-truth files.
