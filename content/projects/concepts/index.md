---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Concepts"
summary: " "
authors: []
tags: [sem1, w3, t, nb]
categories: []
date: 2023-07-01T09:58:49+01:00
weight: 3
# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

“_Concepts are the glue that holds our mental world together_” (Murphy, 2002, p1).

This session will explore recent attempts to model the structure of human concepts. This will involve engaging with a historical debate and distinction between more "statistical" and more "rule-based" models and their implications but also thinking about how our concepts relate to how we categorize things but also how we think and generate new ideas.


## Primary Readings

Everyone should read these and be prepared to discuss.

|  |  |
|:----:|:-----|
| {{< icon name="scroll" pack="fas" >}} Murphy, G. L. (2002) |   Chapter 2, *The big book of concepts*. MIT Press (On Learn)|<!-- {{< details "" >}}{{< icon name="robot" pack="fas" >}} The passage discusses the classical view of categories and concepts, which states that definitions should include all instances of a concept and exclude others. However, this view has been challenged by research showing that real-world concepts often involve multiple complex features and have fuzzy boundaries. The concept of typicality is important in categorization, as people are more likely to consider items that are rated as more typical as belonging to a category. The classical view also suggests that categories can be hierarchically ordered, but there are cases where transitivity fails. The concept of core, representing the "real" concept, does not appear to be an important part of the concept, as there is variation in typicality of category members. The passage also discusses empirical studies on dot patterns and natural categories, which support the idea of prototypes and typicality. Overall, the classical view of categories is not considered a contender among popular theories of concepts. {{</details>}} -->
| {{< icon name="scroll" pack="fas" >}} Goodman, N. D., Tenenbaum, J. B., Feldman, J., & Griffiths, T. L. (2008) | A rational analysis of rule‐based concept learning. *Cognitive Science*, 32(1), 108-154. |<!-- {{< details "" >}}{{< icon name="robot" pack="fas" >}} The article introduces a new model for human concept learning using Bayesian inference. The model is compared to human judgments in category learning experiments and shows good agreement. It explores the use of rule-based representations in concept learning and argues that they can account for graded effects and uncertainty through Bayesian statistics. The article also discusses the behavior of an ideal Bayesian learner and introduces a concept language of rules. It analyzes the behavior of a rational agent learning concepts expressed in this language and formulates the learning problem using Bayesian induction. The article also discusses the probabilities of well-formed formulas in a grammar and introduces a prior probability and likelihood function. The Rational Rules Model is described, and its predictions are compared to human data from several concept learning experiments. {{</details>}} -->

## Secondary Readings

The presenter should read and incorporate these.

|  |  |
|:----:|:-----|
| {{< icon name="scroll" pack="fas" >}} Lake, B. M., Salakhutdinov, R., & Tenenbaum, J. B. (2015). | {{< details "Human-level concept learning through probabilistic program induction. *Science*, 350(6266), 1332-1338.">}}
{{< icon name="robot" pack="fas" >}} 

The article highlights two aspects of human conceptual knowledge that have eluded machine systems: the ability to learn new concepts from just one or a few examples, and the ability to learn rich and flexible representations. The authors propose the Bayesian Program Learning (BPL) framework, which can learn a wide range of visual concepts from just a single example and generalize in ways that are similar to human behavior. BPL represents concepts as stochastic programs and utilizes compositionality, causality, and learning to learn as key ideas.

The authors present a computational model that captures these human learning abilities specifically for simple visual concepts, using handwritten characters from different alphabets as examples. The model represents concepts as simple programs that best explain observed examples, using a Bayesian criterion. In a one-shot classification task, the model achieves human-level performance and outperforms recent deep learning approaches. The model's creative generalization abilities are tested through several "visual Turing tests," which show that in many cases, the model's behavior is indistinguishable from human behavior.


{{< icon name="chalkboard-teacher" pack="fas" >}} This is the first really modern modelling paper on the reading list. It showcases the power of hierarchical Bayesian program induction as a theory of conceptual structure. In being based in symbolic rules/programs, it is a successor to Goodman et al (2008), but  the domain is much more naturalistic and the computational cost of fitting this model is far higher. Note also the differences in writing style compared to the classic papers, e.g. compressed, concise, visual, snappy but key details in an appendix.
 {{</details>}}|
| {{< icon name="scroll" pack="fas" >}} Shepard, R. N., Hovland, C. I. and Jenkins, H. M. (1961) | {{< details "Learning and Memorization of Classifications. *Psychological Monographs: General and Applied*, 75(13), 1.">}}
{{< icon name="robot" pack="fas" >}} The study includes a series of experiments that investigate the learning and memorization of different types of classifications. The results show that the structure of the classification and the complexity of the rules involved affect the difficulty of the task. Overall, the study provides insights into the factors that determine the difficulty of learning and remembering classifications. It highlights the importance of considering the structure of the classification, the complexity of the rules, and the use of different stimuli in understanding the learning and memorization process.

{{< icon name="chalkboard-teacher" pack="fas" >}} The experiments in this paper are long and complicated but what makes it famous is the way Shepard visualizes concepts/classification rules of different complexity (i.e. Figures 2 and 3). These visualizations and the logic behind them are widely used in categorization research and teaching today.
 {{</details>}} |


## Questions under discussion

- How do concepts relate to categories?
- What about to previous topics? e.g. Are concepts representations?

