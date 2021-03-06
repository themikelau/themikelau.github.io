## Research
I am primarily a theorist and am interested in understanding binary star astrophysics using a range of approaches: Monte Carlo population synthesis, analytical calculations, back-of-the-envelope estimates, and hydrodynamical simulations. In particular, I am interested in studying progenitors of gravitational wave mergers and the formation of double compact objects.

### COMPAS
My research group is developing and using the *Compact Object Mergers: Population Astrophysics and Statistics* ([COMPAS](https://compas.science/)) suite, which simulates the evolution of binary stars rapidly (taking only around a second to evolve one binary system from birth to death). This evolution is unlike that of single stars, as binaries interact in many ways. One star may transfer material to another (mass transfer). If runaway transfer occurs, the stellar material may engulf the binary system (common-envelope phase). Tidal interactions may also affect the spin of the stars. Binary orbits shrink and circularise as they radiate gravitational waves, ending in a merger (and [Nobel prize](https://www.nobelprize.org/prizes/physics/2017/press-release/) :) ).

<figure>
  <img src="/images/common-envelope-evolution.png" alt="Common envelope evolution" style="width:100%" class="center">
  <figcaption>Cartoon of a double neutron star formation channel (see Bhattacharya & van den Heuvel (1991), Tauris & van den Heuvel (2006)).
  </figcaption>
</figure> 

### Detecting Double Neutron Stars with *LISA* (Lau et al., 2020 (MNRAS); [arXiv:1910.12422](https://arxiv.org/abs/1910.12422))
I have led a project to understand the population of double neutron stars expected to be seen by *LISA*. The [Laser Interferometer Space Antenna (LISA)](https://lisa.nasa.gov/) is a space-based gravitational wave interferometer with planned launch in the 2030s. It consists of three satellites in heliocentric orbit, arranged in an equilateral triangle constellation. Laser beams connect these satellites, forming 2.5 million kilometre arms that measure distortions in spacetime caused by passing gravitational waves.

My collaborators and I used a synthetic population of double neutron stars evolved with COMPAS, and tracked the gravitational wave-driven evolution of these systems through the LISA frequency window. For our particular assumptions about binary evolution physics and the double neutron star merger rate, we estimate that LISA may be able to detect ~ 35 double neutron stars over a four-year mission, with signal-to-noise ratios above 8 and characteristic orbital frequencies of 1 mHz. Most of these double neutron stars will be Galactic, but ~ 1 system may also be detected in the Large and Small Magellanic Cloud. 

Interestingly, we also think that LISA may be able to detect double neutron stars with significantly eccentric orbits (e ~ 0.1). Eccentricities are difficult to detect with the LIGO and Virgo interferometers, which are sensitive to much higher frequency gravitational waves (1 - 1000 Hz). At such high frequencies, orbits of binary compact objects have to a very good approximation completely circularised through gravitational radiation reaction. We also demonstrated that the eccentricity distribution of double neutron stars may inform us about the formation channel of double neutron stars, such as the stability of the case BB mass transfer episode.

<figure>
  <img src="/images/LISAanimation.gif" alt="Frequency-eccentricity evolution" style="width:70%" class="center">
  <figcaption>This is an animation I have made that shows the evolution due to gravitational radiation reaction of double neutron stars in frequency-eccentricity space over 10 Gyr. Each point represents a double neutron star simulated with COMPAS (Vigna-Gomez et al., 2018). A shear flow is observed that reflects faster evolution for high eccentricity (and high frequency) orbits.</figcaption>
</figure> 

 <figure>
  <img src="/images/LISAnoiseCurve.png" alt="LISA noise curve" style="width:70%" class="center">
  <figcaption>Plot of the LISA noise curve with 35 Monte Carlo realisations of LISA double neutron star sources (filled circles). The green circles correspond to sources in the Large Magellanic Cloud. The height of a dot above the solid curve gives the source signal-to-noise ratio.</figcaption>
</figure> 