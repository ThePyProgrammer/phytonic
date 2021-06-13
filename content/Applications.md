---
typora-root-url: /home/lyc/Documents/LocalDev/physics-website/static/
katex: true
weight: 6
---

# Applications of Feynman Diagrams

## Significance of Feynman Diagrams

With its simplicity and elegance, the Feynman Diagram has been applied liberally in particle physics explanations. Using just a bunch of lines and squiggly lines, Feynman was able to explain and solve problems involving subatomic particle interactions easily. His diagrams are brilliant illustrations that allowed us to predict other particle interactions after constructing a single example.

But it hasn't always been this way. When the first Feynman diagram was published, few physicists believed that it was a rigorous answer to the perplexing inconsistencies when dealing with "[Self-Energy](https://www.wikiwand.com/en/Self-energy)". Yet while Schwinger and Tomonaga's mathematical explanations were impressive, they were too complex to be applied effectively when we need to analyse more complicated interactions between more particles.

**The first Feynmann Diagram published in 1949**

![The first Feynmann Diagram published in 1949](https://physics.aps.org/assets/be0eeb33-4bba-4208-9bf9-2587acdf9c7c/e3_1.gif)

<p style="text-align:center"> <em>Source: Google Images</em></p>

Fortunately, Dyson showed later in a classic paper that the 3 brilliant scientists' methods were equivalent. And for their work, they received the joint [Nobel Prize in Physics for 1965](https://www.nobelprize.org/prizes/physics/1965/summary/).

## Common applications

### Radioactive Decay

#### $\beta^-$ decay

In $\beta^-$ decay, we have a neutron spontaneously converting into a proton, an electron and an anti-neutrino. This can also be written as:

$$
n \to p^+ + e^- + \overline{v}
$$
This can be represented using a Feynman diagram too! Let's take a look (note that the vertical axis is space, while the horizontal axis is time):

![beta-minus-decay](/images/beta-minus-decay.png)

Wait, but what's $d$, $u$, $W^-$ and so on? Let's summarise it in the following table:

| Symbol | Name       | Description                    |
| ------ | ---------- | ------------------------------ |
| $d$    | Down quark | Makes up matter                |
| $u$    | Up quark   | Makes up matter                |
| $W^-$  | W boson    | Particle mediating weak forces |

It may seem a bit strange, but recall that a neutron consists of 1 up quark and 2 down quarks, while a proton consists of 2 up quarks and 1 down quark. Thus, by converting a down quark to an up quark, a neutron can become a proton! 

With that out of the way, let's look at the first diagram more closely. The top two solid lines represent the conversion of a down quark to an up quark, that's easy. Since we have a change in the flavour of quarks, we know that the weak force is involved here. Thus, we must have a $W$ boson acting as the middle-man. By applying conservation of charge on the top vertex, we can determine that it must have a charge of $-1$.

{{< expand "Help! I want a more verbose explanation!" >}}

Try looking at the diagram below (convince yourself that they both represent the same process!):

![electrons repelling each other, with 2 photons](/images/weak-force-diagram.png)

<p style="text-align:center"> <em>Source: Google Images</em></p>

Let's zoom into what happens when a neutron decays into a proton. In the diagram, we can see that the neutron and proton have 2 common quarks; the only difference between them is that the neutron has a 2nd down quark while the proton has a 2nd up quark. When the process occurs, the down quark of the neutron first changes *flavor* to become the up quark of the proton. As the flavor of the quarks is changed, the weak force is at play here (by definition), and the boson emitted must either be the $W$ boson or the $Z$ boson. The $W$ bosons are charged while the $Z$ boson is neutral, so since there is a change in charge (the charge of the down quark is $-\frac{1}{3}$ while the charge of the up quark is $+\frac{2}{3}$), the boson must be a $W^-$ boson to conserve charge.

{{< /expand >}}

Now, the second vertex is where things start to get more interesting. The interaction doesn't stop at the first vertex since the $W^-$ boson disappears eventually. For this to happen, the $W^-$ boson emits an electron to conserve charge. When we learned $\beta^-$ decay, many of us probably wondered why an anti-neutrino is produced. It seemed very arbitrary, but here we see a rather nice explanation. According to the rules of Feynman diagrams, we must **conserve lepton number**. So far, we only have a lepton exiting ($e^-$), because the $W^-$ boson is not a lepton. Thus, there must be another lepton that is entering! 

But...how do we get such a lepton? Since this is not physically possible, we will use the mathematically equivalent explanation that an anti-lepton must be leaving the vertex. Therefore, an anti-neutrino must also be emitted. 

We draw another line, but this time, we have to direct it *backwards in time* to indicate an antiparticle. That's how we predict the existence of the anti-neutrino, and scientists have confirmed that through experiments.

## Fundamental applications

### Exchange forces, again

As mentioned in the previous sections, forces that we usually think of being due to a certain field can be explained using particle physics too! Here's a handy summary for easy referencing.

| Fundamental Force | Mediator      |
| ----------------- | ------------- |
| Weak Force        | W and Z boson |
| Strong Force      | Gluon         |
| Electromagnetic   | Photon        |
| Gravity           | Graviton*     |

*not confirmed yet, but this is the current scientific consensus

Do you remember what the forces we usually experience fall under?

{{< expand "See answer">}}

Electromagnetic forces! Normal force and friction are macro-level observations of repulsions between the charged particles of different atoms when you try to squish them close together.

{{< /expand >}}

To illustrate how these particles mediate these forces, let's look at a few examples (in fact, the nuclear decay explanation above is an instance of weak force in action).

### A pair of electrons, EM Force and Weak Force

What happens when two electrons collide into one another?

Well, they'll repel each other and fly apart, because like charges repel right? Usually, that is indeed what happens when we have a virtual photon mediating the EM force between the two, which we see in the following Feynman diagram:

![electro-mag](/images/electro-mag.png)

In fact, this is also known as Moller scattering. However, there is also another possible cause of this repulsion, albeit less common. That is, the $Z$ boson could have been a mediator for a weak interaction between the electrons. Note that the $Z$ boson and not the $W$ boson is involved, because we have a neutral intermediate due to the conservation laws of particle interactions.

![electro-weak](/images/electro-weak.png)

### Explaining the Strong Force

What about the strong (nuclear) force? The strong force is mediated by gluons. They are responsible for the attractive and repulsive forces between quarks.

![electrons repelling each other, with 2 photons](/images/protons-neutrons-gluons.png)

<p style="text-align:center"> <em>Source: Google Images</em></p>

In this diagram, the whitish curly lines represent the gluons. You could say that gluons 'glue' quarks together!

![electrons repelling each other, with 2 photons](/images/nuclear-strong-force.png)

<p style="text-align:center"> <em>Source: Google Images</em></p>

This is a diagram representing the strong nuclear force, or the repulsion between a neutron and a proton. Don't worry if it looks complicated! Some extra knowledge is required to understand this Feynman diagram, which is beyond the scope of this website. Nevertheless, we hope to give you a taste of what the strong force looks like in Feynman diagrams. To understand this Feynman diagram, you have to realize that quarks, in addition to their flavors (up, down, charm, strange, top, bottom), have color charges (red, green, blue). Anti-quarks also have their own anti-color charges (anti-red, anti-green, anti-blue). Gluons each come with a color charge and an anti-color charge (and hence there are 9 possible color combinations of gluons). Gluons are constantly exchanged between quarks, and you can see their color interactions in this diagram. With all these interactions, the net effect is that the proton and neutron are repelled from each other.

## Summary

To summarise, these are the primitive vertices for the strong, electromagnetic and weak forces. 

![electrons repelling each other, with 2 photons](/images/comparison-of-forces.png)

<p style="text-align:center"> <em>Source: Google Images</em></p>

How about gravity? Well, there are no diagrams for gravity because gravitons haven’t been observed (yet). Feel free to refer to the earlier diagrams to see how these primitive vertices fit together to build the larger diagram! If you think you have understood everything so far, [try out the exercises](../try-it-yourself/) we have prepared next to test your understanding!

