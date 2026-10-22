# Academic Papers

Papers written during my M.Sc. in Data Science at Hochschule Fulda. Each PDF is in this
repository; the summaries below say what the paper does and what my contribution was.

---

## Probabilistic Inductive Miner: Balancing Accuracy, Simplicity and Trust in Process Discovery

Master Seminar: Algorithms in Process Mining, Hochschule Fulda
Supervised by Prof. Dr. Norbert Ketterer
Co-authored with Rohit Suryaa Saravanan

Process discovery turns an event log into a process model, judged along dimensions that pull
against each other: fitness, precision, simplicity, and soundness as a correctness condition.
The Inductive Miner framework (Leemans, Fahland and van der Aalst, 2013) was the first to
guarantee a sound and fitting model in finite time, but it reads the directly-follows graph as a
set of binary facts, which makes it fragile on logs containing deviations. The report explains how
the Probabilistic Inductive Miner of Brons, Scheepens and Fahland repairs that fragility while
preserving soundness.

**My contribution (first half):** reconstruction of the 2013 framework, its guarantees, its
polynomial instantiation and its rediscoverability result; isolating the assumption that breaks on
real data; stating the three requirements PIM was built to satisfy; and assessing its published
evaluation.

The report concludes that PIM does not dominate on every dimension, and that its evaluation
supports a narrower claim: within a framework that still guarantees soundness, it reaches a
region of the accuracy and simplicity trade-off that industrial analysts were shown to prefer.

[Read the paper](https://github.com/suhasnu/academic-papers/blob/main/Probabilistic%20Inductive%20Miner%20Seminar%20Report.pdf)

---

## Co-Citation Analysis on Data Mining and Random Forest: A Literature Review

M.Sc. Data Science, Hochschule Fulda
Sole author

A bibliometric study of how research on data mining and Random Forest is actually connected.
Using 1,205 articles retrieved from Web of Science, I built a co-citation map and analysed the
resulting structure.

Five clusters emerged, all application-driven: geospatial environmental modelling and risk
assessment, landslide susceptibility prediction, machine learning for hydrological and
environmental systems, educational systems and behaviour modelling, and educational data mining
including learning analytics.

The main finding is structural rather than methodological: environmental and geohazard research
overlap heavily in method, while educational research sits largely isolated despite using the same
algorithms. The paper closes on where method exchange across those clusters would be most
valuable, and on open questions around interpretability and hyperparameter optimisation outside
the environmental domain.

[Read the paper](https://github.com/suhasnu/academic-papers/blob/main/Co-citation%20Analysis%20on%20Data%20Mining%20and%20Random%20Forest-%20A%20Literature%20Review.pdf)

---

These are coursework papers, shared for reference. Please cite them if you use anything from them.
