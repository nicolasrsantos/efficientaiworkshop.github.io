---
layout: default
---

## Welcome to the Efficient AI Workshop!

The rapid growth of AI, driven by large datasets and foundation models, has brought remarkable advances but also steep computational, memory, and energy costs. This workshop focuses on efficient AI through data and model reduction, covering techniques such as pruning, quantization, distillation, parameter-efficient fine-tuning, dataset condensation, and coreset selection. By bringing together researchers from machine learning, data mining, and applied AI, we aim to foster discussion on scalable and data-efficient solutions for modern AI systems, including emerging challenges in foundation models and LLMs.

## Call for Papers

We invite original, unpublished research papers on the challenges and advances in data and model efficiency for scalable AI. Accepted papers will be presented as posters, with a subset selected for oral presentations, and published in the IEEE BigData 2026 Workshop Proceedings by the IEEE Computer Society Press. All submissions are reviewed through a double-blind process by members of the program committee.

{% capture topics_content %}
We encourage the submission of papers on topics within the areas listed below. Submissions are not restricted to these specific topics, and we welcome any work that aligns with the general goals of the workshop.

**Model Efficiency and Compression**
- Model pruning, sparsification, and quantization
- Knowledge distillation and model compression
- Parameter-efficient fine-tuning (e.g., adapters, LoRA)
- Low-rank and tensor-based model reduction
- Efficient inference and dynamic computation (e.g., token pruning)

**Data Efficiency and Reduction**
- Dataset condensation and distillation
- Coresets and subset selection
- Graph reduction (e.g., coarsening, sparsification, or condensation)
- Efficient learning over graph-structured and relational data
- Data pruning and synthetic data for efficient training

**Efficiency in Foundation Models and LLMs**
- Efficient post-training, fine-tuning, and adaptation of foundation models
- Prompt compression and context reduction
- Retrieval-efficient RAG systems
- Memory and KV-cache optimization
- Efficient reasoning, retrieval, and agentic workflows for LLMs

**Systems and Scalability for Efficient AI**
- Scalable pipelines for data and model efficiency
- Distributed and memory-efficient training
- Hardware-aware optimization

**Applications of Efficient AI**
- Efficient large-scale real-world applications (e.g., remote sensing, healthcare, recommender systems)
- Edge, mobile, and on-device learning
- Resource-constrained AI for low-compute or low-connectivity environments
- Practical deployments demonstrating efficiency, scalability, and usability

**Trustworthy, Interpretable, and Measurable Efficient AI**
- Explainability of compressed or reduced models
- Trade-offs between efficiency, accuracy, robustness, and cost
- Benchmarks, metrics, and protocols for efficiency-quality-cost trade-offs
- Theoretical insights into data and model reduction
{% endcapture %}

<details open>
<summary>Topics of Interest</summary>
{{ topics_content | markdownify }}
</details>

### Submission Guidelines

{% capture guidelines_content %}
- **Format:** Submissions must be a PDF file in IEEE 2-column format, following the IEEE Computer Society Proceedings Manuscript Formatting Guidelines (see [formatting instructions](https://www.ieee.org/conferences/publishing/templates.html)).
- **Paper types:** We accept both **full papers** (up to 10 pages) and **short papers** (up to 5 pages). References are counted within the page limit. A **GenAI disclosure statement is required** and does not count toward the page limit.
- **Review:** This workshop uses double-blind review. Author names and affiliations must be removed from the submission. Papers that are not properly anonymized will be desk-rejected without review.
- **Presentation:** At least one author of each accepted paper must register and present the work in person at Phoenix, AZ, USA.
{% endcapture %}

<div class="submission-guidelines">
{{ guidelines_content | markdownify }}
</div>

### Submission Site

All submissions must be made through the [Cyberchair submission portal](https://wi-lab.com/cyberchair/2026/bigdata26/scripts/submit.php?subarea=S40&undisplay_detail=1&wh=/cyberchair/2026/bigdata26/scripts/ws_submit.php).

## Important Dates

- **Paper submission deadline:** October 29, 2026
- **Notification of acceptance:** November 16, 2026
- **Camera-ready deadline:** November 23, 2026
- **Workshop date:** TBD (between December 14–17, 2026)

## Invited Speakers

*To be announced.*

## Organizers

<div class="organizers-grid">
  <div class="organizer-card" style="grid-column: 1/3">
    <a href="https://nicolasrsantos.github.io/" target="_blank"><div class="organizer-photo"><img src="images/nicolas.jpg" alt="Nícolas Roque dos Santos" style="object-position: center 3%;"></div></a>
    <a href="https://nicolasrsantos.github.io/" target="_blank" class="organizer-name">Nícolas Roque dos Santos</a>
    <span class="organizer-role">Postdoctoral Researcher</span>
    <span class="organizer-affil">UC Riverside</span>
  </div>
  <div class="organizer-card" style="grid-column: 3/5">
    <a href="https://yezil3.github.io/" target="_blank"><div class="organizer-photo"><img src="images/yezi.jpg" alt="Yezi Liu"></div></a>
    <a href="https://yezil3.github.io/" target="_blank" class="organizer-name">Yezi Liu</a>
    <span class="organizer-role">PhD Candidate</span>
    <span class="organizer-affil">UC Irvine</span>
  </div>
  <div class="organizer-card" style="grid-column: 5/7">
    <a href="https://www.cs.emory.edu/~wjin30//" target="_blank"><div class="organizer-photo"><img src="images/wei.jpg" alt="Wei Jin"></div></a>
    <a href="https://www.cs.emory.edu/~wjin30//" target="_blank" class="organizer-name">Wei Jin</a>
    <span class="organizer-role">Assistant Professor</span>
    <span class="organizer-affil">Emory University</span>
  </div>
  <div class="organizer-card" style="grid-column: 2/4">
    <a href="https://agupta2304.github.io/" target="_blank"><div class="organizer-photo"><img src="images/aman.jpg" alt="Aman Gupta"></div></a>
    <a href="https://agupta2304.github.io/" target="_blank" class="organizer-name">Aman Gupta</a>
    <span class="organizer-role">Principal ML Engineer</span>
    <span class="organizer-affil">Nubank</span>
  </div>
  <div class="organizer-card" style="grid-column: 4/6">
    <a href="https://www.cs.ucr.edu/~epapalex/" target="_blank"><div class="organizer-photo"><img src="images/vagelis.jpg" alt="Evangelos Papalexakis"></div></a>
    <a href="https://www.cs.ucr.edu/~epapalex/" target="_blank" class="organizer-name">Evangelos (Vagelis) Papalexakis</a>
    <span class="organizer-role">Professor</span>
    <span class="organizer-affil">UC Riverside</span>
  </div>
</div>

## Contact

For inquiries, please reach out at [efficientaiworkshop@gmail.com](mailto:efficientaiworkshop@gmail.com).
