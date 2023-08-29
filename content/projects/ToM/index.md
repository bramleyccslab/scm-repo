---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Theory of Mind"
summary: " "
authors: []
tags: [sem1, w10, t]
categories: []
date: 2023-07-01T09:58:49+01:00
weight: 17
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


*“Here is how it works: first you decide to treat the object whose behavior is to be predicted as a rational agent; then you figure out what beliefs that agent ought to have, given its place in the world and its purpose. Then you figure out what desires it ought to have, on the same considerations, and finally you predict that this rational agent will act to further its goals in the light of its beliefs.”* (Dennett, The Intentional Stance, 1996, p. 17).


This session will think about how people reason about others and how we might make machines that can do the same.


## Primary Readings

Everyone should read these and be prepared to discuss.

|  |  |
|:----:|:-----|
| {{< icon name="scroll" pack="fas" >}} Dennett, D. C. (1981). | {{< details "Chapter 3: True believers: The intentional strategy and why it works. In *Mind Design II*">}}
<!-- {{< icon name="robot" pack="fas" >}} This excerpt from "Mind Design II" explores belief attribution. The passage presents two opposing views on belief attribution: realism and interpretationism. The author argues that belief is an objective phenomenon that can be discerned through the intentional strategy, which treats the object of study as a rational agent with beliefs and desires. The passage emphasizes the effectiveness of the intentional strategy in predicting human behavior and addresses objections raised against it. It also discusses the relationship between an organization and its environment, the role of internal representations, and the reasons why the intentional strategy works. The author explores the belief that most beliefs must be true, the distinction between belief and opinion, and the challenges with language-of-thought models. -->
{{< icon name="chalkboard-teacher" pack="fas" >}} Some philosophy for a change. If you've not heard of Dennett, he is one of the most influential philosophers of cognitive science and has some interesting views on consciousness, free will and many other things (evolution, religion). He is also known for this 'intentional stance' idea which helps clarify what it means to think about the private mental states of others.{{</details>}} |
|  {{< icon name="scroll" pack="fas" >}} Jara-Ettinger, J., Gweon, H., Schulz, L. E., & Tenenbaum, J. B. (2016). | {{< details "The naïve utility calculus: Computational principles underlying commonsense psychology. *Trends in Cognitive Sciences*, 20(8), 589-604.">}}
 <!-- {{< icon name="robot" pack="fas" >}} The article proposes human social cognition is structured around a basic understanding of ourselves and others as intuitive utility maximizers: From a young age, humans implicitly assume that agents choose goals and actions to maximize the rewards they expect to obtain relative to the costs they expect to incur. It argues this ‘naïve utility calculus’ allows both children and adults observe the behavior of others and infer their beliefs and desires, their longer-term knowledge and preferences, and even their character: who is knowledgeable or competent, who is praiseworthy or blameworthy, who is friendly, indifferent, or an enemy. The article reviews studies providing support for the naïve utility calculus, and shows how it captures the rich social reasoning humans engage in from infancy. -->
{{< icon name="chalkboard-teacher" pack="fas" >}} Fast forward 30 years from Mind Design, and we see the intentional stance ideas startign to be formalized in computational Bayesian framework, capturing how one can *invert* behaviours to identify someone's likely beliefs, values etc. Note also the connections with Development and Rationality topics.{{</details>}} |

## Secondary Readings

The presenter should read and incorporate at least two of these.

|  |  |
|:----:|:-----|
|  {{< icon name="scroll" pack="fas" >}} Baker, C. L., Saxe, R., & Tenenbaum, J. B. (2009). | {{< details "Action understanding as inverse planning. *Cognition*, 113(3), 329-349.">}}
{{< icon name="robot" pack="fas" >}} This article presents a computational framework for modeling human action understanding using Bayesian inverse planning. The authors conducted psychophysical experiments to assess the accuracy of different inverse planning models in predicting human goal inferences. The results show evidence for a rational inference mechanism in human goal inference. The framework provides a formal approach to understanding rational action and goal inference in humans.

{{< icon name="chalkboard-teacher" pack="fas" >}} Here's a more detailed example of this project modelling theory of mind style inferences as rational inverse planning. The food truck scenarios are proven popular and sprouted 'spinoff' projects in the decade since this paper.{{</details>}} |
|  {{< icon name="scroll" pack="fas" >}} Heider, F., & Simmel, M. (1944).  | {{< details "An experimental study of apparent behavior. *The American Journal of Psychology*, 57(2), 243-259.">}}
 {{< icon name="robot" pack="fas" >}} The study aimed to understand how individuals perceive and interpret the behavior of others based on visual stimuli. The authors highlight the lack of experimental investigations in this area and emphasize the importance of studying the psychology of perception in relation to apparent behavior. The study involved showing participants a moving picture-film featuring geometric shapes moving in various directions and speeds. Participants were asked to describe the pictures and answer questions about them. The findings revealed that participants tended to interpret the movements as actions of animate beings, attributing personalities and motives to the shapes. The study demonstrates that humans have a tendency to perceive and attribute behavior to abstract shapes, suggesting a fundamental psychological process involved in perceiving others' behavior.

{{< icon name="chalkboard-teacher" pack="fas" >}} This very old article is really most famous for its stimuli (https://www.youtube.com/watch?v=VTNmLt7QX8E). One still tends to see this clip in the introduction to talks about social cognition (its not a bad idea to include it in your own presentation!). It is striking how irresistible it is to take ``the intentional stance'' a la Dennett, and assign motivations and personality traits to these simple geometric shapes being moved around on an overhead projector.{{</details>}} |
|  {{< icon name="scroll" pack="fas" >}} Baron-Cohen, S., Leslie, A. M., & Frith, U. (1985). | {{< details "Does the autistic child have a “theory of mind”? *Cognition*, 21(1), 37-46.">}}
{{< icon name="robot" pack="fas" >}} This article explores whether autistic children lack a "theory of mind," which refers to the ability to understand and predict the beliefs and behaviors of others. The study compares the performance of autistic children to that of normal children and children with Down's syndrome using a puppet play paradigm. The research suggests that despite having a higher mental age than the comparison groups, autistic children fail to impute beliefs to others, indicating a deficit in meta-representational development specific to autism. This deficit contributes to the social impairment experienced by autistic children. The authors propose a new model of meta-representational development that suggests the capacity to form "second-order representations" is necessary for a theory of mind. Autistic children not only struggle with social ineptness but also exhibit a lack of pretend play.

{{< icon name="chalkboard-teacher" pack="fas" >}} Again this paper is most famous for its stimuli, the 'Sally-Ann False Belief Task' which probes whether someone is capable of Theory of Mind reasoning. Who is Simon Baron-Cohen's famous cousin?{{</details>}} |
<!-- | {{< icon name="scroll" pack="fas" >}} Richardson, H., Lisandrelli, G., Riobueno-Naylor, A., & Saxe, R. (2018). | {{< details "Development of the social brain from age three to twelve years. *Nature Communications*, 9(1), 1-12.">}}
{{< icon name="robot" pack="fas" >}} This study examines the development of the "social brain" in children aged three to twelve. The researchers investigate how the neural networks involved in thinking about others' bodies and minds change as children develop. They found that these networks become increasingly distinct throughout childhood, and their functional maturity is related to the correlation between them. The milestone of passing false-belief tasks, often used to measure theory of mind development, does not align with the development of the social brain.

The study used fMRI to identify divisions of labor within the adult social brain and aimed to understand the neural changes that support the development of children's understanding of others' minds. The results suggest that the regions involved in reasoning about others' minds and bodies are functionally distinct by the age of 3 and become increasingly specialized between the ages of 3-12. There was also a distinct neural response to others' minds and bodies even before children pass explicit false-belief tasks.

The study found that children who passed false-belief tasks and had more distinct responses across brain networks showed more adult-like responses to the movie in each network.{{</details>}} | -->

## Questions under discussion

 - Can you think of situations where people make the wrong theory of mind ascriptions (i.e. something with little or no mental life that we we assume does have it, and visa versa)?
 - What are some challenges for developing artificial agents with theory of mind
 - Is the Baron-Cohen view of autism still current?


