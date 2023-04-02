# Purple
Outlining a model to implement AGI
## Abstract
This work is a speculation of a system or systems that allow the emergence of behaviors which can be considered as intelligent behavior. Although it might be more similar to a sci-fi story, but recent achievements and the research momentum on AGI, almost guarantee that many of these intelligent behaviors actually emerge from the tools we build.

_- The true value of science fiction to me is that it permits speculation (Asimov)_
## Introduction
Intelligence has various definitions in different domains[^1]: emotional, social, street smart, etc. 
Which one do we mean by general intelligence?

DeepMind has come to the conclusion
that to build intelligent "Reward is enough"[^2].
OpenAI is more focused on scaling transformer models which has been summarized into "Gradient descent can do it[^3]".
And referring to the Turing test, DeepMind, OpenAI, Anthropic,
Meta and others built systems that are indistinguishable from humans in a conversation to an extreme extent.
Yet it can be evidently argued that these are not AGI[^4].

## Design concepts 
I introduce principal elements and core concepts to later on propose the initial design, but I don't know deeply what are the ways to implement these principals and concepts:

**Principle 1.** I define **intelligence** as a subjective and relative phenomena. It's our perception of intelligence that matters. The base idea comes from the Turing test.
I expand that definition to a broader one: A system is intelligent if we **perceive** intelligence from it.

Alternatively: A system is not inherently intelligent, it's intelligent if we sense it's intelligent.

**Principle 2.** Explainability: Designing AGI is by itself hard and embedding explainability from the beginning makes adds unnecessary complexity.
The fact that we humans, as a benchmark of intelligence, struggles to explain why we do something is the core of this unnecessary complexity.
Also, the non-deterministic nature of our decision-making process is a key for intelligence. (e.g. Even most sophisticated humans might do unreasonable things).
On the other hand, I believe if you don't see unexpected behavior from a system, there's no curiosity in the behavior of that system. And if curiosity is important for intelligence, then lack of unexpected behavior means there's no intelligence (Artificial Curiosity).
So I will exclude explainability from this research and propose to use control mechanisms that help us stay safe rather than having a white-boxed explanation of an AI decision-making process.

**Concept 1.** Our intelligence is limited to "**domain-sets**": meaning we can't apply the same amount of intelligence to everything in life. Someone might be exceptional with her muscle memory in playing the piano but not very sharp in understanding chemistry or even not as good with another instrument like a guitar. A high-IQ person might be a distinguished scientist but normally not able perform a complex surgery. 

Characteristics of domain-sets:
- Everyone can introduce their own domain-sets. I (or this model) don't define domain-sets.
- Everyone that perceives intelligence from a system on a domain-set can claim that the system is intelligent in that domain. For example, a programmer can build a calculator program and claim that the calculator is intelligent in the arithmetic domain-set.

Defining domain-sets is outside the boundaries of this design. And I'm not using domain-sets to test if a system is AGI or not. Later on, I introduce a broader test to detect AGI.
The role of domain-sets in this design is to distinguish and respect different types of intelligence and not limit the definition of intelligence to this design or to some tasks. 

My aim is to have as many scoring systems as we can over different domain-sets by many researchers and turn measuring intelligence into an endless research topic. Meanwhile, design a system that we think can be intelligent in practice. Additionally, defining domain-sets allows having concepts like "foolish intelligent": an entity that we consider intelligent but still call it foolish in certain situations.

Note: Similarly, (or ironically), that's how we've been evaluating human intelligence with different intelligence tests, e.g. the IQ tests.

**Concept 2. story**: A story is a chain that articulate the dynamics inside a domain-set. For example, an intelligent person might be able to make sense of symbols in a math equation and see a way to prove it. An intelligent person might recognize the dynamics of a game, etc. 

Each of these is an example of a domain-set. In any domain-set, there's a dynamic of how things are connected to each other and how we can exploit them to our benefit. When a system recognizes those dynamics, either by itself or by learning from others, it has the ability to turn what it has learned into a form called **story**. A story is an articulation of a finding. 

Characteristics of stories:
- Stories aren't complete, they're fragments, so they have no limitation in nature, but in implementation there might be limitations in terms of bytes or characters.
- Stories can be received and understood but not bit by bit. Meaning that they aren't objective and absolute, they are subjective and relative. (Subjective Intelligence)
- Stories find their own place in the receiver's knowledge base and build new connectors to understand more stories.
- Stories can be used to communicate between AI models.

Stories are self-reinforcing. Meaning they form the understanding of a model, what it desires, what it considers good or bad.

**Concept 3.** One human can be supersmart still won't do much on earth, but a collection of humans plus time, will be change the world. Some examples of previous works in AI and algorithm design that addressed this concept are: agent-oriented design, particle swarm analysis, ant colont, etc. But almost all of them neglect the value of one small idea while that’s actually how humanity works.

Note: Our intelligence is collective. Curiosity in communication turns into being noisy; if there's a collective model with no amount of being noisy, there's no curiosity inside.

## Live Free Models
Supposing having an implementation of these concepts, the resulting system comprises many models that are interacting together. I call each of these models a Live Free Model(LFM). Any LFM knows its objective at any given time and constantly is updating it.
A set of LFMs form something we call a **Purple.**

## Purple
A Purple is a set of LFMs which we can communicate with.

## How to use Purple
Purple, (or any other implementation of AGI) is different from normal tools we have. It can be simpler to use or more difficult. Like a person. 

On the other hand, we sometimes use other humans.
Some ways that come to mind when we want to get something from a person are:
1. Using them, persuading them
2. Trade with them
3. Collaborate with them
4. Serve them 

etc.

If we truly build AGI, it will have its own agenda, and we need to answer its needs or give it what it wants or persuade it to give us the answers. 

It might have an answer for understanding the secrets of the universe or a way to travel to far galaxies, etc. And we might not understand how that answer works, but we might also use it.

 
## Open Questions
1. Staying alive: should the model show a will to live?
2. Minimize pain: everything we do can be modeled as pain minimizing. is this an angle that helps the design?
3. Boredom and laziness: should the model show boredom and laziness?
4. Difference between average agents and genius agents
5. I believe the key for a better AI is to model the way learn and represent things not the structure of our brain
How each person builds its understanding and starts to generalize
6. Stories aren’t real, and yet they’re meaningful: how we create mental paths between two abstract concepts and later on use them for other concepts
7. We need a little bad memory, forgetting: To be a mathematician, you need a slightly bad memory [🔗](https://twitter.com/nabeelqu/status/1610267023694770179?s=20&t=x27uXfUd6zlQLPL3a4nH7g)
8. Imagination in the AGI
9. Giving positive bias to weird ideas
10. What intelligence are we building? Dumb, normal, intelligent
11. When we decide to believe someone/something? (how do we decide in the mafia game)


## AGI Test
As discussed in C0, intelligence is based on our perception and from our perception a model like GPT-4 can be considered intelligent.
I define a threshold that surpassing that indicates AGI.
A system is AGI not when it's indistinguishable from a human in conversation but when it can design another AGI. 

For example, Since GPT-4 can't build another AGI, it's not AGI.

This definition seems so simple that I believe somebody else has thought about it before. So in that case, I too give my vote to this definition of AGI.
There's also and ultimate version of this test where a system autonomously and independently came to conclusion to build another system to delegate computation to it. (without a prompt or ask)

# Vision papers
What is a vision paper?

[https://scienceplusplus.org/visions/index.html](https://scienceplusplus.org/visions/index.html)


# Personal Motivation and Story
The Motivation of this work, beside the Asimov novels and years of working on AI projects, started in October 2021. 
AI has always been a part of my professional career, but it was the first conversation topic that I had with the person I love. 

In October 2021 something terrible happened, and it made something inside me to flip. I wasn't aware of it, but that event made me work on AI more than before in my free time, unconsciously. Months later, I noticed it in myself. I was thinking that if I create AI, that first conversation will be restored and love will find its way to me.


It might seem cool to work on AGI, but it was also mad and unrealistic, starting from nothing and from nowhere. At that period, our data team at Eveince[^5] was working on graph neural networks to build a better representation of texts for better understanding of financial advice given by experts on the internet[^6] so I was more focused on graphs networks. But then I came to the conclusion that graphs inherently and generally are not a good tool to represent behaviour when they represent data and vice versa [^7]. 

This wasn't a step toward a design, rather a step toward removing designs that don't work. This led me to read more and search more where I found almost all the available network architectures empty of characteristics required to build AGI, but then again small lights in the path like this tweet from LeCunn kept me going [^11]. 
<p></p>
<p align="center">
<img src="/resources/Lecunn-tweet.png" width="600">
</p>

Studying DeepMind and OpenAI works has also made me draw some predictions over the next months, not to feel good about my predictions but to test if I was right that current networks are not what we're looking for [^8]. 


On April 25th 2022, the ICLR 2022 was held. One of the most important events of introducing cutting-edge achievements in AI, sponsored by DeepMind, Google Research, Two Sigma, Microsoft, Meta, etc. (DeepMind's' overview of their papers for ICLR [^9]). And I started to see a convergence between my findings and what was reflected in the "Bootstrapped Meta-Learning[^10]." 

I articulated my ideas as a basis for more research even though interesting works at the time like Gato, DALL-E and GPT were on a different path. Those models progressed dramatically over the past year, but I was thinking maybe it's better to call them computation models. 

And for AGI, I took another direction which has been depicted here as Purple.

## The name, why Purple
I chose the name in March 2023, after over a year since it was started. There were three mysteries about this work that formed its identity for me:

**First:** What is the right design, one powerful model or a population of models?
In this design, I chose the population, based on this thought that a single human wouldn't be intelligent if it was one baby on an isolated island. 

Intelligence emerges from a population of models, not a single model. It's essential to have live models that each one has its own experiences and stories and has the ability to interact and communicate with other models. True intelligence emerges from this population of models, not a single model.

For a counter design, LeCun's proposal[^13] is more focused on one powerful model and its general ability of learning, which is absolutely important but doesn't introduce a specific way for models to learn from each other.

**Second:** There's a famous paradox called the Moravec's Paradox (1988)[^14]: _"it is comparatively easy to make computers exhibit adult level performance on intelligence tests or playing checkers, and difficult or impossible to give them the skills of a one-year-old when it comes to perception and mobility."_

This paradox has been used by robotic researchers where they had difficulty in problems like coordinating hand-eye tasks while computers were really amazing at computation. 

How can a model feel like us? and ultimately learn like us? Learning is the key to intelligence, but mimicking learning is not enough. So I came to this conclusion that our feelings are something that will stay unique to us humans. The way we interact with the world can be simulated, but it will never be how we do it. So this paradox should always be true at some level.

**Third:** In a society, how do we prioritize our goals and wants against others? If we're living with others, where we rely on society rules and where we rely on morality? How do we value our thoughts and thoughts from other people?

Answering this question is key to understanding our relationships. Our ability to make friends, start a conversation or living together. If an AI model directly doesn't address this, of course, to some extent, the model has not been successful in creating a stable population of models.

Live Free Models (LFMs) inherently have the ability to create stories from themselves and learn stories from others. They create their own goals from those stories, and teach each other, and judge each other, and through these constant interactions they find solutions to problems. Then again, these solutions are incomplete and partial, but they cover a specific scope of a problem.


**Purple** These mystries for me were full of contradictory concepts. I felt Purple reflects how two different colors, blue and red, create a new color while they seem contradictory.


[^1]: https://en.wikipedia.org/wiki/Intelligence
[^2]: https://www.sciencedirect.com/science/article/pii/S0004370221000862
[^3]: https://twitter.com/sama/status/1638983750934724608
[^4]: https://www.nature.com/articles/s41562-022-01516-2
[^5]: https://eveince.com
[^6]: https://www.hup.harvard.edu/catalog.php?isbn=9780674576186
[^7]: https://arxiv.org/abs/2211.16103
[^8]: https://arjmandi.substack.com/p/on-the-edge-5
[^9]: https://arjmandi.substack.com/p/on-the-edge-11
[^10]: https://www.deepmind.com/blog/deepminds-latest-research-at-iclr-2022
[^11]: https://openreview.net/pdf?id=b-ny3x071E5
[^12]: https://twitter.com/ylecun/status/1492604977260412928
[^13]: https://openreview.net/pdf?id=BZ5a1r-kVsf
[^14]: https://www.hup.harvard.edu/catalog.php?isbn=9780674576186

