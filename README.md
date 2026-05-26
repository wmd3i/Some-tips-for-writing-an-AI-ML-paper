# Some Tips for Writing an AI/ML Paper

**Author:** Haipeng Chen  
**Affiliation:** Assistant Professor, William & Mary

***Your paper is the medium of your work.*** It is a shame if you do the quality work but are not able to convey that with the quality writing. It is extremely helpful to keep reading good papers and understand how they are written, and use those skills in your own writing. The following principles and section-specific tips may help when writing an AI/ML paper.

---

### Principle 1: Write a Holistic and Consistent Narrative

Writing the **abstract**, **introduction**, and **main body** is like looking at the same item from different scopes:

- The **abstract** is like a telescope.
- The **introduction** is like looking with bare eyes.
- The **main body** is like using a microscope.

However, you are always looking at the **SAME ITEM**.

Therefore, the paper should remain consistent throughout. Key claims should be reiterated several times across the paper.

For example:

- The **Related Work** section should illustrate the gap in existing work.
- The **Methodology** section should support the claims about novelty and technical contributions.
- The **Experiments** section should support the claims about effectiveness.

---

### Principle 2: Researchers Help Researchers

Do your best to minimize the readers' and reviewers' effort in understanding the paper.

> You make reviewers happy; reviewers make you happy.

Guidelines:

- Avoid overly long sentences and paragraphs.
- Avoid mumbling.
- Be upfront.
- Avoid unnecessary delayed explanations or long wind-ups.
- Be logical.
- Revise the paper from the perspective of readers and reviewers.

---

## Abstract

An abstract usually has four parts:

1. **General background**  
   What broad theme is the paper about?

2. **Gap and challenges**  
   What is missing in existing work? What challenges remain?

3. **Proposed method**  
   What method do we propose? What is new in our method?

4. **Results**  
   What do the theoretical and empirical results look like?

---

## Introduction

The introduction is an expanded version of the abstract.

The rest of the paper is a further expansion of the introduction.

---

## Related Work

The goals of the Related Work section are to:

1. Show that we have a good understanding of the literature.
2. Show that there is a gap in existing work that our paper aims to fill.

### How to Efficiently Conduct a Literature Review for AI/ML Papers

1. **Identify keywords** related to the topic.

2. **Search for recent papers** from top AI/ML venues, especially papers from the last two years.  
   Example venues include: ICLR, ICML, NeurIPS, AAAI, RLC. Also check the **Related Work** sections in these papers. These are papers that we **must include**.

3. **Expand the search** using Google Scholar.  
   Include less recent papers or papers from other venues when appropriate.

4. **Create a literature list**, for example using Google Sheets.

5. **Skim and filter papers** by reading abstracts and quickly reviewing the full paper.  
   Gauge quality and relevance, then select the top papers to read more thoroughly.

These selected papers are the ones that we may need to compare with.

---

## Reference Styles

### BibTeX Guidelines for Conference and Journal Papers

#### Journal Articles

Use `@article`.

Required fields:

- `author`
- `title`
- `journal`
- `year`

Optional fields:

- `volume`
- `number`
- `pages`
- `doi`

#### Conference Papers

Use `@inproceedings`.

Required fields:

- `author`
- `title`
- `booktitle`
- `year`

Optional fields:

- `pages`

### Rule of Thumb

- Prefer peer-reviewed versions over arXiv whenever applicable.
- Do not include location, such as city or country.
- Do not include publisher.
- URLs are fine for arXiv or OpenReview, but remove hyperlinks.

---

## Preliminary and Methodology

The preliminary section is optional.

For the methodology section:

- Use visuals to explain the method whenever appropriate.
- Start with **why**, then explain **what** or **how**.
- Focus on **our method**.
- The ultimate goal is to highlight what is new in the proposed method.
- Tell a story, not a list of bullets.
- Be clear, concise, and **consistent**.
- Always explain the notation the first time it appears.
- Justify design choices.
- Explain why specific methods or models are chosen.
- Use visuals to illustrate model architectures whenever possible.
- Use algorithm blocks for methodological pipelines whenever possible.

---

## Equations

When writing equations:

- Be consistent about whether equations end with commas or periods.
- Avoid unnecessary space between text and equations to save space.
- References to equations should use `Eq.\eqref{}`.

Important details:

1. Use no space between `Eq.` and `\eqref{}`.
2. Use `\eqref{}` instead of `\ref{}`.
3. Capitalize the first letter: use `Eq.` instead of `eq.`.

---

## Experimental Results

Before starting experiments, create a concrete and thorough plan.

The plan should include: Tables & Figures to include in the paper; Expected runtime. The plan may be adjusted later.

### What to Include in the Experiment Section

1. **Research questions or hypotheses**

2. **Experimental setting**

   Include: (1) Datasets (2) Model architectures (3) Implementation details (4) Hardware setup (5) Software setup
   (6) Evaluation metrics (7) Baselines

3. **Results and discussions**

### Common Components of Results and Discussions

Usually, this section includes:

1. A core result.
2. An ablation study, especially for a new algorithm.
3. Auxiliary results, such as:
   - Visualizations
   - Exploratory results
   - Interpretation

---

## Code Submission

Most conference submissions encourage code submission.

Because many conferences use double-blind review, code should be submitted as an anonymous package.

Options include:

- Using Anonymous GitHub.
- Uploading an anonymous code package directly.

---

## Summary Checklist

Before submitting an AI/ML paper, check that:

- [ ] The abstract, introduction, and main body tell the same story.
- [ ] The paper clearly states the research gap.
- [ ] The methodology supports the novelty claim.
- [ ] The experiments support the effectiveness claim.
- [ ] Sentences and paragraphs are concise.
- [ ] The related work covers recent and relevant literature.
- [ ] BibTeX entries follow the correct format.
- [ ] Notation is explained when first introduced.
- [ ] Methodological choices are justified.
- [ ] Equations are referenced consistently.
- [ ] Experiments are planned before running.
- [ ] Results include core findings, ablations, and auxiliary analyses.
- [ ] Visuals are used where helpful.
- [ ] Anonymous code is uploaded as an appendix when appropriate.
