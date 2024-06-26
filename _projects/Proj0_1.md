---
title: "Hallucination Detection and Mitigation in NMT"
excerpt: " <img src='Screenshot 2023-06-26 at 10.55.58 PM.png' width='500' height='500' align='left'>
We explored data manipulation techniques, explainability, prompt engineering, and unsupervised approaches (using attention matrices) to detect and mitigate hallucinations in Neural Machine Translation.
[(Repo Link)](https://github.com/AnganaB/Hallucinations_NMT)<br>
<br>
<br>
<br>
<br>
<br>
 "
collection: projects
---

We study hallucinations in neural machine translation (NMT), which lie at the extreme end of machine translation pathologies. Initially, we use perturbation methods to induce hallucination in translation tasks and understand the magnitude of performance changes in NMT models, using evaluation metrics like BLEU and METEOR. We next device hallucination detection via text classification and NMT. First, for the text classification-based hallucination detection task, we use BERT and analyze its performance using explainability techniques like Integrated Gradients. This motivates us to approach data manipulation techniques like tagging, perturbation, and prompt engineering mechanisms. Finally, for the NMT-based hallucination detection, we use an unsupervised approach to detect hallucinations by utilizing attention matrices in translation models. Upon experimentation, we find that perturbation using misspelled words leads to high degradation in translation performance for NMT models (46% reduction in BLEU score). Additionally, data manipulation, prompt engineering, and the use of attention lead to better performances in neural models. 

