# Purple
Outlining a model to implement AGI
## Abstract
This work is a speculation of a system or systems that allow the emergence of behaviors which can be considered as intelligent behavior. Although it might be more similar to a sci-fi story, but recent achievements and the research momentum on AGI, almost guarantee that many of these intelligent behaviors actually emerge from the tools we build.

_- The true value of science fiction to me is that it permits speculation_
## Introduction
Intelligence has various definitions in different domains[^1]: emotional, social, street smart, etc. 
Which one do we mean by general intelligence?

DeepMind has come to the conclusion
that to build intelligent "Reward is enough"[^2].
OpenAI is more focused on scaling transformer models which has been summarized into "Gradient descent can do it[^3]".
And referring to the Turing test, DeepMind, OpenAI, Anthropic,
Meta and others built systems that are indistinguishable from humans in a conversation to an extreme extent.
Yet it can be evidently argued that these are not AGI[^4].

# Design concepts 
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
Supposing having an implementation of these concepts, the resulting system should know it's winning objective at any given time.
## The name, Purple
Moravec paradox
Purple contradictions amongst cohesion and cohisive. individual and society. want and need.




genius works, like understanding the secrets of the universe are things that can be resolved, traveling to far galaxies, etc. they are questions that should be entered to this machine, that machine provides us the answer, we don't understand it, but we can use it


---


Now that we've [built big models](https://arxiv.org/pdf/2203.15556.pdf), and we're lining up GPU racks can also be a good opportunity to look for other ways too.

- --


smart people see some patterns and connections to exploit. many of the hard problems get solved this way. a way of designing intelligence. and on the side it raises a question that are these connections these people make related to their brain structure? are the connection that people with high eq make related to their brian?



[https://www.linkedin.com/posts/yann-lecun_ai-activity-6932436820454502400-hV39/?utm_source=linkedin_share&utm_medium=android_app](https://www.linkedin.com/posts/yann-lecun_ai-activity-6932436820454502400-hV39/?utm_source=linkedin_share&utm_medium=android_app)




[https://www.cold-takes.com/ai-could-defeat-all-of-us-combined](https://www.cold-takes.com/ai-could-defeat-all-of-us-combined)

- ****Common Sense Comes Closer to Computers****
 [https://www.quantamagazine.org/common-sense-comes-to-computers-20200430/](https://www.quantamagazine.org/common-sense-comes-to-computers-20200430/)

- ------

As a researcher in the field, I don't find definitions like "adaptive behavior" suitable for what we mean by intelligence.

(In reinforcement learning, we define intelligence as getting more rewards.)Using activation functions to build models that can imitate learning through gradient descent. A very practical way but we still don't have AGI.

[*Despite observing intelligence among other species, the way I see intelligence works amongst us humans is 1) a combination of different abilities and behaviors and 2) certainly not the ability to drive, eat, etc ..*]


[https://twitter.com/nabeelqu/status/1610267023694770179?s=20&t=x27uXfUd6zlQLPL3a4nH7g](https://twitter.com/nabeelqu/status/1610267023694770179?s=20&t=x27uXfUd6zlQLPL3a4nH7g)

Better understanding intelligence
[https://kirkegaard.substack.com/p/iq-can-be-increased-by-more-education](https://kirkegaard.substack.com/p/iq-can-be-increased-by-more-education)


[Collective intelligence - Wikipedia](https://en.wikipedia.org/wiki/Collective_intelligence#:~:text=Collective%20intelligence%20(CI)%20is%20shared,appears%20in%20consensus%20decision%20making.)


[Yann LeCun on a vision to make AI systems learn and reason like animals and humans](https://ai.facebook.com/blog/yann-lecun-advances-in-ai-research/)


[Shaped](https://www.shaped.ai/blog/yann-lecun-a-path-towards-autonomous-machine-intelligence)

[Yann LeCun's Paper on creating autonomous machines](https://datasciencelearningcenter.substack.com/p/yann-lecuns-paper-on-creating-autonomous)

[pdf](https://openreview.net/pdf?id=BZ5a1r-kVsf)


I  "*sense of intelligence*": Things that make us call some behavior intelligent, and I use this definition as one of the metrics to evaluate either a system is intelligent or not.
If we consider different senses we expect a system to show, then we can rank different account systems in terms of their coverage on different senses.

**Concept 3.** Intelligence can be **learned**: When an intelligent person finds the physics of a domain-set and exploits it to her benefit, we can learn from them. We might not be able to apply the same level of intelligence in that domain-set, but we learn that example. Also, an intelligent person is a receiver of thoughts and solutions from others. So solutions should be able to be sent and received by
 
# Open Topics
1. Staying alive: should the model show a will to live?
2. Minimize pain: everything we do can be modeled as pain minimizing. is this an angle that helps the design?
3. Boredom and laziness: should the model show boredom and laziness?
4. Difference between average agents and genius agents
5. I believe the key for a better AI is to model the way learn and represent things not the structure of our brain
How each person builds its understanding and starts to generalize
6. Stories aren’t real, and yet they’re meaningful: how we create mental paths between two abstract concepts and later on use them for other concepts
7. We need a little bad memory, forgetting 
8. Imagination in the AGI
9. Giving positive bias to weird ideas
10. What intelligence are we building? Dumb, normal, intelligent
11. When we decide to believe someone/something? (how do we decide in the mafia game)


# AGI Test
As discussed in C0, intelligence is based on our perception and from our perception a model like GPT-4 can be considered intelligent.
I define a threshold that surpassing that indicates AGI.
A system is AGI not when it's indistinguishable from a human in conversation but when it can design another AGI. 

For example, Since GPT-4 can't build another AGI, it's not AGI.

This definition seems so simple that I believe somebody else has thought about it before. So in that case, I too give my vote to this definition of AGI.
There's also and ultimate version of this test where a system autonomously and independently came to conclusion to build another system to delegate computation to it. (without a prompt or ask)

# Vision papers
What is a vision paper?

[https://scienceplusplus.org/visions/index.html](https://scienceplusplus.org/visions/index.html)


# Personal Motivation Story
The Motivation of this work, beside the Asimov novels and years of working on AI projects, started in October 2021. 
AI has always been a part of my professional career, but it was the first conversation topic that I had with the person I love. 

In October 2021 something terrible happened, and it made something inside me to flip. I wasn't aware of it, but that event made me work on AI more than before in my free time, unconsciously. Months later, I noticed it in myself. I was thinking that if I create AI, that first conversation will be restored and love will find its way to me.


It might seem cool to work on AGI, but it was also mad and unrealistic, starting from nothing and from nowhere. At that period, our data team at [Eveince](https://eveince.com) was working on graph neural networks to build a better representation of texts for better understanding of financial advice given by experts on the internet [here](https://arxiv.org/abs/2211.16103). and I was reading about and thinking about graphs networks. But then I came to the conclusion that graphs inherently and generally are not a good tool to represent behaviour when they represent data and vice versa [On the Edge #5](https://arjmandi.substack.com/p/on-the-edge-5). 

This wasn't a step toward a design, rather a step toward removing designs that don't work. This led me to read more and search more where I found almost all of the available network architectures empty of characteristics I was looking for but then again small lights in the path like [this tweet](https://twitter.com/ylecun/status/1492604977260412928) from LeCunn kept me going. Studying Deepmind and OpenAI works has also made me draw some predictions over the next months, not to feel good about my predictions but to see if I was right and current architectures are not what I'm looking for, this might help me to find the design.  [On the Edge #11](https://arjmandi.substack.com/p/on-the-edge-11). 


On April 25th 2022, the ICLR 2022 was held. One of the most important events of introducing cutting-edge achievements in AI, sponsored by DeepMind, Google Research, Two Sigma, Microsoft, Meta, etc. DeepMind published an overview of their papers for ICLR in [this post](https://www.deepmind.com/blog/deepminds-latest-research-at-iclr-2022). And I started to see a convergence between my findings and what was reflected in the "[BOOTSTRAPPED META-LEARNING](https://openreview.net/pdf?id=b-ny3x071E5)". 

I articulated my ideas as a basis for more research even though interesting works at the time like Gato and DALL-E were on a different path. They've progressed dramatically over the past year into new versions or models like PALM-E. I categorize them as new computation tools, and for AGI I took another direction which has been depicted here as Purple.


[^1]: https://en.wikipedia.org/wiki/Intelligence
[^2]: https://www.sciencedirect.com/science/article/pii/S0004370221000862
[^3]: https://twitter.com/sama/status/1638983750934724608
[^4]: https://www.nature.com/articles/s41562-022-01516-2
[^]:
[^]:
[^]:
[^]:
[^]:
[^]:
[^]:
[^]:
[^]:
[^]:
[^]:
