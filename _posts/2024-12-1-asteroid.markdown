---
layout: post
title:  "Friend or Foe or Other: ‘Asteroid City’ as an AI metaphor"
categories: Essays
---

*Originally written for [Beyond Code](https://issuu.com/beyondcodemagazine/docs/copy_--_beyond_code._issue_01_compu_60999fdafe2b4b) magazine.*

Wes Anderson’s Asteroid City (2023) is in no way “about” AI. However, we can read it through a lens that helps us make sense of AI and the culture around it. In fact, Wes Anderson’s whole filmmaking style illustrates the ways our intellectual cultures try to abstract, simplify, and understand the new “exotic, mind-like entities”[^1] that have appeared in our midst.

Let’s set the scene: At a science fair in the film’s titular desert town, Jeffrey Wright’s general – General Grif Gibson – addresses a group of aspiring astronomers, their parents, and Boy Scouts. He thunders: “If you wanted to lead a nice, quiet, peaceful life, you picked the wrong time to be born.” 

Then, an alien arrives.

Once the alien shows up, the film shifts gears tonally. US government G-men show up to quarantine the film’s characters under force of arms. Quarantined, the captives cannot help but wonder, each in their own way, what the alien means. A teacher tells her students, “There are still nine planets!” A defiant pupil retorts: “Except now, there’s a alien.” [sic]. Another boy breaks into song:

> Dear alien, who art in heaven,
> 
> Lean and skinny, ‘bout six foot seven:
> 
> Though we know ye ain’t our brother:
> 
> Are you friend or foe? (Or other?)


<div style="text-align: center;">
  <img src="/images/asteroid.png" alt="singing kids" width="800em"/>
  <p style="margin-top: 8px; font-style: italic;">...or other?</p>
</div>

And so on.

Six months before Asteroid City’s release, OpenAI launched the first version of ChatGPT, a chat-agent instantiation of their GPT-3 language model. This variant caught fire with the general public; people were disturbed, excited, or both at the same time. Some changed their career plans. Others declared the singularity imminent. But in the intellectual establishments of the Western world, many commentators adopt a smug, nothing-new-under-the-sun voice. Some labeled these models as “stochastic parrots”, dumb automatons that simply remix their training data using statistical tricks. Another word for this posture is denial. “There are still nine planets.”

***

Everyone knows Wes Anderson’s penchant for symmetry and his association with a (now much-parodied) visual vocabulary that spawned a thousand coffee-table books. Under the surface of his famous “aesthetic”, Anderson’s approach to depicting the world reflects an understanding of reality based on stylized abstraction. One gets the sense that, rather than depicting something as it happened, Anderson constructs models of what happened, dioramas that reduce things to their main constituent parts, with a priority put on style. In a way, it’s a Cartesian approach: abstract away noise, chaos, and dirt; rebuild the world as an elegant scheme with mathematical precision and, correspondingly, beauty. Anderson seems to say: all films simplify the world, so why not turn that simplification into a fully realized art?

Fittingly, machines are important in Anderson’s films. Machines take his simplification schema to the extreme. Take the cocktail-maker from Asteroid City:

<div style="text-align: center;">
  <img src="/images/martini.png" alt="Martini machine" width="200em"/>
  <p style="margin-top: 8px; font-style: italic;">The Martini machine from 'Asteroid City'</p>
</div>

When we see Anderson’s Martini machine, it is immediately comprehensible: one part squeezes the lemon, another shakes the drink and adds ice, another pours. The machine has been reduced to things humans can understand. Anderson’s machines are like toys that work: simplified representations and functioning equivalents to the real thing. 

We all, to various extents, live in this kind of mental world. We reduce machines, systems, people, theories into parts. Or we make sense of them in terms of other machines or even anthropomorphize them.

The purpose of such abstraction is not simplicity, but understanding, even insight. Wes Anderon’s machines (and his narratives) are satisfying because they put everything you need to understand them on the surface and point giant arrows at them; the satisfaction of simplification is the pleasure of understanding.

In short, Anderson’s machines, like his film worlds, are reductive surrogates of the real thing. These coherent, simplistic, schematic equivalents abstract away the dirt and incoherence of human experience.

***


In the field of Artificial Intelligence, things used to be inherently logical: AI systems were composed of a straightforward set of rules that needed only to be represented to be explained, so the map was the territory. The infamously convincing Eliza chatbot from the 1970s  can be reduced to fairly simple pseudocode. These things made inherent sense. Even more complex models, like expert systems or decision trees, could be likened to long lists of rules; in a Wes Anderson diegesis, the avatar for such AI systems would be a vaguely Austro-Hungarian clerk poring over a comically large ledger while wielding a mechanical calculator.

However, as models grew not just more complex but ontologically transformed from lists of rules to nonlinear networks, the representation of the model and the actual model began to diverge, dramatically. You cannot draw a modern neural network, especially not in its transformer variety. Its operations do not make schematic sense to human thought. The map and the territory look nothing alike. How do we understand such a model?

The growing need to bridge the map and the territory has spawned the field of Explainable AI (XAI). There is something very Wes Anderson-ish about this approach, and examining XAI helps us both understand the appeal of Wes Anderson’s simplification filmmaking and the appeal of similar moves in AI research.

Let’s say our model involves a thousand parameters, nonlinear functions, and multiple layers of computation. How do we explain what it does? Among the answers is an intriguing approach: surrogate models. These look at the model’s behavior and create a second, much simpler model that approximates that behavior. 

Now, that simple toy model is taken as somehow “explaining” the original one. But this is misleading: our toy model correlates with the target model’s behavior but bears no ontological relationship to it[^2]. The explanation it produces is a post-hoc one.

<div style="text-align: center;">
  <img src="/images/diagram.png" alt="Flowchart showing how toy model represents target model" width="800em"/>
  <p style="margin-top: 8px; font-style: italic;">The relationship between a surrogate and target model.</p>
</div>

Note that in this flowchart the surrogate toy model is in no way connected to the internal essence of the “complicated AI model” – it only has access to its inputs and outputs.

What makes such an explanation good? XAI has no well-established Kuhnian paradigm yet[^3]; criteria abound. For instance, frequently XAI practitioners score their surrogate models not by whether they cast light on their target model’s internal workings, but on whether they agree with human explanations. In other words, in some situations, a satisfying explanation to human observers is held up as the goal rather than a faithful explanation (whatever that might mean). 

This emphasis on psychological closure is also a driving force of Wes Anderson’s filmmaking and provides one of the main pleasures of watching his films.

Could a modern, connectionist AI fit into a Wes Anderson film? Almost certainly not. It could not be depicted. In fact, the Asteroid City visibly struggles to depict even an organic, non-artificial alien coherently.

![](/images/alien.png)

When the alien arrives, Anderson’s models break down: the alien’s descent is shown in an upward-facing shot of the sky, something rarely seen in the Euclidean film. The alien is clearly not of this world. While all characters are played by human actors, the alien is a stop-motion animation moving in a completely different rhythm, without any attempt to make him look “realistic”. We never properly see his ship. Basically, the alien makes no sense in the world of the film. The descent is like the arrival of a visitor in the novel Flatland: that 19th-century classic depicts a two-dimensional world into which a third-dimensional visitor arrives, throwing the flat society into chaos.

The difficulty in depicting the alien is not a failure of the movie; rather, this formal break is a dramatization and visual enactment of the fact that some realities simply cannot be accommodated inside the elegant simplicity of Wes Anderson’s dioramas. Similarly, modern AI is not some Steampunk machine that can be cleanly broken into constituent parts. There is no good “toy version” of GPT-4; at least not one that makes a lot of sense.

<div style="text-align: center;">
  <img src="/images/backstage.png" alt=""/>
  <p style="margin-top: 8px; font-style: italic;">“I don’t play him as an alien, actually. I play him as a metaphor”, says the stage actor playing the alien in this behind-the-curtain scene from Asteroid City.</p>
</div>



Yet everywhere you look, intellectuals crave comprehensible metaphors: “stochastic parrot”, “merely a statistical model”, “mad libs”, “monkeys at typewriters”, “echo chamber”, “glorified autocomplete”. This need for physical metaphors is the desire for a world that is reducible to toy models. Wes Anderson knows this craving for simplification and the satisfaction it brings; this may account for much of his popularity.

The film’s characters ask, in various ways, if the alien is “friend”, “foe”, or “other”. A friend or a foe is someone that makes sense in your world. But an “other” is beyond it, a metaphysical threat. The anxiety this “other” induces is the film's central theme. And this anxiety that haunts us, too. The need to “abstract away” what is new, and perhaps frightening, about Generative AI fuels the desire to lean on old metaphors and previous ways of seeing. When it comes to engaging with AI, we may prefer a friend to a foe, but we may yet prefer a foe to an “other”. 

In this way, Asteroid City is a warning: a two-dimensional world cannot contain a three-dimensional entity. How do we bridge the gap? Asteroid City’s answer seems to point back to itself: to art. The film’s characters may be stuck in Flatland, but we are looking down from beyond, this time from our movie theater seats. In dramatizing this higher-dimensional intrusion from the outside, the film catapults the audience beyond the flat. 

We may not be able to satisfyingly explain a transformer or neural net to the lay public or even to ourselves. But when we can use art to dramatize an encounter with the unexplainable, we get a chance to stand still and look at it, or even just look at our own incomprehension instead of explaining it away. To contemplate ignorance and true novelty, rather than drown it in ham-fisted metaphors, might just be the beginning of an understanding. In this way, sometimes art can go where science can’t.


[^1]: Shanahan, Murray. 2023. “Talking About Large Language Models.” arXiv. https://doi.org/10.48550/arXiv.2212.03551.

[^2]: For more on the philosophical stakes of toy surrogate models, see Páez, Andrés. 2024. “Understanding with Toy Surrogate Models in Machine Learning.” Minds and Machines 34 (4): 45. https://doi.org/10.1007/s11023-024-09700-1.

[^3]: Freiesleben, Timo, and Gunnar König. 2023. “Dear XAI Community, We Need to Talk! Fundamental Misconceptions in Current XAI Research.” arXiv. https://doi.org/10.48550/arXiv.2306.04292.



