
# Diffraction & Interference ![icon](imgs/diIcon.png)
---

One of the most counter-intuitive, and fundamental, principles of Quantum Mechanics is *wave–particle duality*: the concept that every quantum-scale object exhibits behaviors that cannot be fully described as either a particle or a wave alone.  In order to fully describe a quantum-scale object's behavior, both of these seemingly mutually exclusive paradigms must be used.
In this lab you will observe diffraction and interference of light, phenomena that can only be described and use your observations to measure the wavelength of the light.

Background
---------------------

Quantum Mechanics was developed in the early 1900's, but the evidence for it began to appear even in the late 1800's. 
For example, Heinrich Hertz noticed that sparks started more rapidly when electrodes were illuminated with ultraviolet (UV) light. 
Other investigators later determined that free charges (*i.e.*, electrons) were emitted from metal electrodes illuminated by UV light. 
These were called "photoelectrons". 
Some metals, mostly the alkali metals in the first column of the periodic table, produced a steady supply of photoelectrons (called a "photocurrent") when illuminated by either UV light or visible light, but other metals only did so for UV light. 
Detailed measurements of this "photoelectric effect" established the following characteristics:

1.  For a given metal, there exists a definite cut-off frequency, $\nu_0$. 
    Incident light with frequency below $\nu_0$ produces no photocurrent regardless of its intensity.

2.  For light with frequency $\nu>\nu_0$,
    the magnitude of the photocurrent produced is directly proportional to the intensity of the incident light.

3.  The maximum kinetic energy of the photoelectrons does not depend on the intensity of the light, but it is 
    proportional to the frequency of the incident light.

These characteristics could not be explained by the classical description of light as a wave that continuously transmits energy in proportion to the intensity of the light. 
Explaining these observations required a different description for light, which was proposed in papers by Max Planck (1901) and Albert Einstein (1905).[^1]

They proposed to describe light as consisting of discrete bundles of energy, rather than as a continuous stream of energy. 
The bundles, or "quanta", of energy were named *photons*. 
Each photon carries an energy of $E=h\nu$, where $h$ is Planck's constant with units of energy times time. 
The name of this constant honors Planck because he was the first to use the idea of quanta to explain the blackbody radiation spectrum. Einstein then used it to explain the photoelectric effect as follows.

A photon of incident light transfers all of its energy to an electron in the metal. 
If that energy is sufficient, it can dislodge the electron from the metal, 
*i.e.*, it does some amount of work, $W$, to overcome the potential energy binding the electron in the metal. 
Any excess energy goes into the kinetic energy of the ejected electron,
$$
E= W +\frac{1}{2} m v^2 
$$
Using the photon energy, $E=h\nu$, we get
$$
\frac{1}{2} m v^2 =h\nu -W
$$

Not every electron in the material experiences the same potential, so the work required to eject them varies and their resulting kinetic energy varies. 
However, there is a minimum amount of work required for the most loosely bound electrons, which corresponds to a maximum kinetic energy for the ejected electrons. 
We can measure that maximum kinetic energy by applying a "stopping voltage" which the photoelectrons must overcome to be detected. 
If we call $V$ the voltage required to stop the most energetic electrons (and all the other electrons as well, of course), then $eV_s = \frac{1}{2}mv_{\rm max}^2$. Putting this all together we get the expression
$$
V_s =h\nu/e -\phi
$$
where $\phi$ is called the "work function" of the metal and corresponds to the minumum work required to eject an electron from that particular type of metal. 
Since we divided through by $e$, the work function $\phi$ has units of volts.

This equation is a straight line on a graph of $V_s(\nu)$, with a slope of $h/e$ and a $y$-intercept of $\phi$. 
By measuring $V_s$ for different frequencies of light and fitting such a line we can determine both Planck's constant and the metal's work function.


Instruments
---------------------