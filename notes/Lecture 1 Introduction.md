# Lecture 1: Introduction
**Date**: 2026-Jun-04 

**Key Focus**: 
The intersection of computer vision and deep learning, tracing the field's evolution from its biological origins to the modern AI breakthroughs that enable machines to perceive, understand, and interact with the visual world.

## 📚 Course Content | 💡 Personal Reflections

| Course Content | Personal Reflections |
| --- | --- |
| **The Biological Context of Vision:** Vision is a cornerstone of intelligence. Evolutionary history (like the Cambrian Explosion) and neuroscience—specifically Hubel and Wiesel's 1959 experiments on hierarchical receptive fields in the visual cortex—deeply inspired early computer vision. | **Nature as an Engineering Blueprint:** It is fascinating how the foundational architecture of artificial Convolutional Neural Networks (CNNs) is a direct translation of biological findings. Biology remains one of our best guides for computational design. |
| **Milestones, the AI Winter, & ImageNet:** The field faced an "AI Winter" where progress stalled despite algorithms like Backpropagation (1986) existing. The real breakthrough required the convergence of compute and massive data—specifically the ImageNet dataset (2012) and AlexNet. | **The Humbling Reality of the "AI Winter":** Hearing about decades of stalled progress is a stark reminder that algorithmic brilliance isn't enough. High-capacity models essentially lay dormant until massive datasets like ImageNet became available, highlighting that data is the ultimate engine for modern AI. |
| **Modern Tasks Beyond Classification:** The field has evolved from simple image classification to semantic/instance segmentation, object detection, multimodal understanding, and generative AI (e.g., diffusion models). The current frontier involves 3D reconstruction and embodied agents. | **Beyond the "What" to the "Where" and "How":** The transition to tasks like instance segmentation and embodied AI shows the rapid push toward true "spatial intelligence." The ultimate goal isn't just a machine that *sees*, but one that can seamlessly *interact* with a 3D physical environment. |

---

## ❓ Unresolved Questions

1. **The Mathematics of Backpropagation:** How exactly are the loss functions formulated, and how do gradients successfully flow backward through millions of parameters without vanishing or exploding?
2. **Deciphering Diffusion Models:** What does the mathematical trajectory look like when generative models "reverse a gradual noising process" to generate coherent images from pure noise?
3. **Mitigating Human Bias:** Since data artifacts carry human biases into AI systems, what specific algorithmic techniques or dataset curation methods are currently considered state-of-the-art for debiasing vision models?
4. **Scaling and Parallelization:** As models expand to trillion-parameter scales, how do systems manage the synchronization between workers across distributed GPU clusters without severely bottlenecking training times?

---

## 📖 Extended Reading

* **The Biological Foundation of Deep Learning:** [Receptive fields of single neurones in the cat's striate cortex](https://pubmed.ncbi.nlm.nih.gov/14403679/) (Hubel, D. H., & Wiesel, T. N., 1959). The breakthrough paper mapping how neurons build complex visual representations.
* **The Philosophy of Computer Vision:** [Vision: A Computational Investigation into the Human Representation and Processing of Visual Information](http://www.colinphillips.net/wp-content/uploads/2015/09/marr1982_ch1.pdf) (David Marr, 1982). A classic text proposing the hierarchical framework of visual processing.
* **The Spark of the Deep Learning Revolution:** [ImageNet Classification with Deep Convolutional Neural Networks](https://www.semanticscholar.org/paper/ImageNet-classification-with-deep-convolutional-Krizhevsky-Sutskever/abd1c342495432171beb7ca8fd9551ef13cbd0ff) (Krizhevsky, A., Sutskever, I., & Hinton, G. E., 2012). The landmark "AlexNet" paper that proved the effectiveness of CNNs and massive datasets.