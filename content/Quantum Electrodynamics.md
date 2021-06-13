---
typora-root-url: /home/lyc/Documents/LocalDev/physics-website/static/
katex: true
weight: 3
---

# Quantum electrodynamics

Combining the ideas of Quantum and Classical Electrodynamics, we have quantum electrodynamics. In essence, Quantum electrodynamics explains the phenomena of electric fields and magnetic fields in terms of the discrete interactions of charged particles and photons.

## A word on momentum transfer

Newton's 2nd Law states that force is the rate of change of momentum ($\vec p$), or $\vec F = \frac{d\vec p}{dt}$. Hence, for an object to exert a force on another, it must transfer momentum, given by $\vec p = m \vec v$. A law governing this transfer is the **Law of Conservation of (Linear) Momentum**: for a system, its momentum must be the same before and after a process has occurred.

![A gun recoiling](/images/gunrecoil.gif)

<p style="text-align:center"> <em>Source: Google Images</em></p>

For example, this phenomena manifests when firing a gun. As the bullet flies forwards, the gun will recoil backwards. Why so? Initially, nothing is moving, so the momentum of the system is $0$. Thus, after firing, the momentums must cancel out to $0$. This is only possible if the gun have an equal momentum to the bullet, but in the opposite direction. This explains why a gun recoils *backwards* when a bullet is fired *forwards*. (Note that this means that when firing a bullet, a force is applied backwards on the gun as well)

In quantum electrodynamics, this concept applies as well. We will see that soon enough in the following sections.

## Explaining why electrons repel

We know that like charges repel. Hence, two electrons, being both negatively charged, will repel when they are close to one another. The classical explanation is that an electric force is exerted due to the presence of an electric field. But how do we explain this in the quantum view? Is momentum somehow related to this?

Yes! In fact, we can reuse our gun firing analogy. Imagine an electron is a gun. When it "fires" a photon (the bullet), it "recoils". Thus, the trajectory of the electron changes. Because the photon carries momentum to the right, and the electron must gain some momentum leftwards to cancel out this initially non-existent rightwards momentum. Hence, it is deflected towards the left.

![electron turn left](/images/repel_left.gif)

Now, instead of emitting a photon, what if an electron is hit by a photon? The photon transfers its momentum to the electron. In this case, the electron absorbs the photon. The rightward momentum of the photon is transferred to the left-moving electron, deflecting it towards the right.

![electron turn right](/images/repel_right.gif)

Now, here comes the magic. Try combining the two halves together. What do you notice?

**This is actually the repulsion of two electrons!**

![two electrons repelling each other](/images/repel_both.gif)

When two electrons move close together, they can exchange photons*. These photons transfer momentum from one electron to another, causing them to repel.

This illustrates a fundamental concept of quantum electrodynamics: **electric forces are mediated by the transfer of momentum by photons.**

## *Stop To Think!

Something seems strange here, doesn't it? Why can photons be exchanged? When the photon is created out of nowhere, isn't the law of conservation of energy violated? See more in [Virtual Particles](../virtual-particles/)!

