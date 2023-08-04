---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Time"
summary: " "
authors: []
tags: [sem1, w7, t]
categories: []
date: 2023-07-01T09:58:49+01:00
weight: 11
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

*“For all the points of the compass, there’s only one direction and time is its only measure.”* (Stoppard, 1966)

Unlike most computational systems, humans experience and must respond to their environment through time. One of the most basic forms of human and animal learning is to associate things that happen close together. Everyday activities like speech, music, dance demand precise time control, while imagination, mental simulation, and memory (“mental time travel”) seem to require encoding of (and ability to regenerate events) in the right temporal sequence. What then is the role of time in the various cognitive processes and representations we have been discussing throughout this course?


## Primary Readings

Everyone should read these and be prepared to discuss.

|  |  |
|:----:|:-----|
| {{< icon name="scroll" pack="fas" >}} Elman, J. L. (1990) | {{< details "Finding structure in time. *Cognitive Science*, 14, 179-211.">}}
{{< icon name="robot" pack="fas" >}} The article discusses the representation of time in connectionist models. It proposes representing time implicitly through its effects on processing rather than explicitly. Recurrent links and hidden unit patterns allow networks to develop internal representations that incorporate both task and memory demands. Simulations show that these representations are context-dependent and can express generalizations across classes of items. The article highlights challenges in incorporating temporal aspects into parallel-processing models and discusses the drawbacks of using a spatial metaphor to represent time. It emphasizes the context-sensitivity of representations and the advantages of distributed representations over symbolic representations.{{</details>}} |
| {{< icon name="scroll" pack="fas" >}} Bramley, N. R., Gerstenberg, T., Mayrhofer, R., & Lagnado, D. A. (2018). | {{< details "Time in causal structure learning. Journal of Experimental Psychology: Learning, Memory, and Cognition, 44(12), 1880.">}}
{{< icon name="robot" pack="fas" >}} This study examines how timing information influences judgments of causal strength and structure induction. Four experiments were conducted, revealing the importance of event order and temporal intervals in learning causal relationships. A Bayesian model accurately predicted participants' judgments, highlighting the significance of time in understanding causal learning.  Participants' judgments were largely explained by event order, but there was some evidence of delay sensitivity and participants were able to distinguish between causal structures based on event timings alone.
{{</details>}} |

## Secondary Readings

The presenter should read and incorporate these.

|  |  |
|:----:|:-----|
| {{< icon name="scroll" pack="fas" >}} Gong, T., Gerstenberg, T., Mayrhofer, R., & Bramley, N. R. (2023). | {{< details "Active causal structure learning in continuous time. Cognitive Psychology, 140, 101542.">}}
{{< icon name="robot" pack="fas" >}} The article discusses active causal structure learning in continuous time, exploring how people learn about causal structure and make intervention choices. The study finds that participants' accuracy depends on the informativeness and evidential complexity of the data they generate. Participants optimize their intervention choices to maximize expected information and minimize inferential complexity. The paper also discusses the computational challenges of active causal learning and the role of metacognitive awareness in successful learning. The findings provide insights into understanding how people learn about causal structure in dynamic environments.{{</details>}} |
| {{< icon name="scroll" pack="fas" >}} Haggard, P., Clark, S., & Kalogeras, J. (2002). | {{< details "Voluntary action and conscious awareness. *Nature Neuroscience*, 5(4), 382-385.">}}
{{< icon name="robot" pack="fas" >}} This article explores the relationship between voluntary action and conscious awareness. The authors argue that our experiences of voluntary action are the result of different stages of neural activity and that the central nervous system must bind these representations together to produce a coherent experience of our own actions. To study the links between representations of voluntary actions and their effects, the authors conducted experiments where subjects reported the perceived times of their actions and consequences. The results showed that voluntary actions and their effects are attracted together across time. Overall, the article provides evidence for a neural mechanism that binds together the perception of voluntary actions and their effects in conscious awareness. This intentional binding is crucial for our conscious experience of free will and our ability to perceive our actions as having an impact on the environment.{{</details>}} |
| {{< icon name="scroll" pack="fas" >}} Grice, G. R. (1948). | {{< details "The relation of secondary reinforcement to delayed reward in visual discrimination learning. *Journal of Experimental Psychology*, 38(1), 1.">}}
{{< icon name="robot" pack="fas" >}} This classic article, published in 1948, explores the relationship between reinforcement and delayed reward in visual discrimination learning. The study involved training albino rats to discriminate between black and white stimuli under different conditions of delay of reward. The results showed that the number of trials required to reach the learning criterion varied based on the duration of the delay, and the type of secondary reinforcement had an effect on the learning process.{{</details>}} |
<!-- | {{< icon name="scroll" pack="fas" >}} Engel, A. K., & Singer, W. (2001). | {{< details "Temporal binding and the neural correlates of sensory awareness. *Trends in Cognitive Sciences*, 5(1), 16-25.">}}
{{< icon name="robot" pack="fas" >}} {{</details>}} | -->


## Questions under discussion

- How veridical is our perception of the time course of events and actions?
- What problem do RNNs try to solve and how well do you think they achieve this?
- How might time help us encode non-temporal things like relations?


