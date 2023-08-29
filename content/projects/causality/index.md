---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Causality"
summary: " "
authors: []
tags: [sem1, w4, t]
categories: []
date: 2023-07-01T09:58:49+01:00
weight: 7
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

The search for a causal understanding of the world is at the heart of human cognition. It shapes learning throughout development and guides intelligent behaviour by allowing cognisers to predict outcomes, selectively gather information, attribute blame and credit, and imagine hypothetical and counterfactual situations. Causal reasoning is also central to the scientific method, underpinning how we, as scientists, design experiments, build and evaluate theories including the ones we use to describe and understand our own minds.

In this session, we will think about how to model the cognition involved in learning, representing and exploiting a causal model of the world.

## Primary Readings

Everyone should read these and be prepared to discuss.

|  |  |
|:----:|:-----|
| {{< icon name="scroll" pack="fas" >}} Coenen, A., Rehder, B., & Gureckis, T. M. (2015).   |  Strategies to intervene on causal systems are adaptively selected. *Cognitive Psychology*, 79, 102-133. | <!-- {{< details "">}} {{< icon name="robot" pack="fas" >}} This research explores different strategies people use when intervening on causal systems to learn about their underlying structure. The study compares two models: the Information Gain (IG) model, which suggests learners should choose interventions that minimize uncertainty, and the Positive Testing Strategy (PTS), which predicts a preference for interventions that activate a high proportion of links in a hypothesis. The findings show that individuals use a mixture of these two strategies and can adaptively alter their behavior based on the success or failure of previous strategies. Time pressure also influences strategy selection.{{</details>}} -->
| {{< icon name="scroll" pack="fas" >}} Pearl, J. (2019). | The seven tools of causal inference, with reflections on machine learning. *Communications of the ACM*, 62(3), 54-60.|
<!-- {{< details "">}}{{< icon name="robot" pack="fas" >}} This article explores obstacles in machine learning systems, such as adaptability, explainability, and cause-effect understanding, and proposes the use of causal modeling tools to overcome these challenges. It discusses the three-level hierarchy of causal reasoning, which involves association, intervention, and counterfactual thinking. Causal diagrams and structural causal models are presented as crucial tools for representing and estimating causal effects from data.{{</details>}}  -->

## Secondary Readings

The presenter should read and incorporate these.

|  |  |
|:----:|:-----|
{{< icon name="scroll" pack="fas" >}} Bramley, N. R., Lagnado, D. A., & Speekenbrink, M. (2015). | {{< details "Conservative forgetful scholars: How people learn causal structure through sequences of interventions. *Journal of Experimental Psychology: Learning, Memory and Cognition*, 41(3), 708.">}}
{{< icon name="robot" pack="fas" >}} This article explores how people learn causal structures through interventions. The researchers developed a computer task where participants learned the structure of probabilistic causal systems. They developed models to understand participants' intervention choices and judgments, considering memory and processing limitations. The study found that successful participants used a model that maximized information gain, forgot evidence from earlier trials, and had conservative beliefs. The study highlights the importance of active learning and the use of simple heuristics in causal structure identification.
{{< icon name="chalkboard-teacher" pack="fas" >}} Like Coenen et al, this is an example of human causal learning through interventions, at rung 2 of Pearl's ladder.{{</details>}} |
| {{< icon name="scroll" pack="fas" >}}  Quillien, T., & Lucas, C. G. (2023).  |  {{< details "Counterfactuals and the logic of causal selection. *Psychological Review*.">}}
{{< icon name="robot" pack="fas" >}} Quillien and Lucas explore the relationship between counterfactuals and causal selection. They propose a counterfactual theory, suggesting that people imagine alternative possibilities and judge causal responsibility based on the correlation between factors across these simulations. The theory is supported by empirical data and experiments. The article discusses the use of a computational model, the Counterfactual Effect Size Model (CESM), to explain human judgments in various studies related to causal attributions and judgments. The CESM is found to have a good fit with the data and is able to predict participants' intuitions accurately.{{</details>}} |
| {{< icon name="scroll" pack="fas" >}}  Pearl, J. (2000/2009) |  {{< details "Causality: Chapters 1-2. (On Learn)">}}
{{< icon name="chalkboard-teacher" pack="fas" >}} This important book laid formal/mathmatical groundwork for causal modelling in data science but also use of bayesian networks as representations of structural knowledge about the world, particularly causal, combining this with principles of probabilistic inference and statistical dependence. It is technical but readable.
{{< icon name="robot" pack="fas" >}} Chapter one of the book introduces the concepts of probabilities, graphs, and causal models. It highlights the importance of probabilities in studying causality, especially in disciplines such as economics, epidemiology, sociology, and psychology. Probability theory helps determine the strength of causal connections and make inferences from noisy observations. The chapter also discusses the use of probabilities in handling exceptions that cannot be processed by deterministic logic. The passage goes on to introduce various concepts within probability theory such as axioms, conditional probabilities, Bayesian inference, joint distribution functions, and graphical models. It explains the properties and terminology associated with probabilities, graphs, and causal models. The chapter also explores the application of probabilities and causal models to hypothesis testing, interventions, and counterfactual analysis.

Overall, these chapters provide a comprehensive introduction to probabilities, graphs, and causal models, highlighting their applications and implications in studying causality.

 {{</details>}} |





## Questions under discussion

- What are the levels of Pearl’s Ladder of Causation?
- What makes an intervention valuable?
- What are counterfactuals and what role do they play in reasoning?

