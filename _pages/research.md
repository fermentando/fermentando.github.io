---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
math: true
---

**The Launching of Galactic Winds from a Multiphase ISM**


Much of our work is dedicated to unraveling how galaxies generate powerful winds containing both hot and cold matter, phenomena that regulate a galaxy’s growth and star formation history. Observations consistently reveal that these winds are laced with cold, clumpy clouds, even though classical theory predicted rapid destruction for such fragile structures. By running high-resolution simulations, we explored how regions of cold gas embedded in a multiphase, inhomogeneous medium (the interstellar medium, or ISM) respond to being swept up by galactic winds. Our findings highlight how complex, realistic conditions actually help cold clouds survive far longer than previously assumed.

Delving deeper into the physics, we found that the enduring presence of cold gas in these winds hinges on a “column density criterion”—the total quantity of cold gas along a wind’s path needs to surpass a value determined by the interplay of turbulent mixing and rapid cooling. When this condition is met, cold clouds not only survive passage but fragment and mix into a strikingly universal mass distribution: a power law with slope \\(dN/dm \\propto m^{-2}\\), known as Zipf’s law. This suggests that both turbulence and radiative cooling work in tandem to reshape the cold phase, regardless of its initial properties, as it is launched into the wind. The cold gas shatters into small filaments and droplets, dramatically increasing its covering fraction, while turbulence efficiently injects energy into every phase. Through this lens, we demonstrate how the underlying physics of entrainment, cooling, and mixing drives the large-scale appearance and long-range transport of cold gas in galactic outflows, bridging the gaps between microscopic cloud survival and the complex patterns seen by astronomical surveys.

<div style="display: flex; gap: 20px; align-items: flex-start;">
  <!-- Video -->
  <figure style="flex: 1;">
    <video controls style="width: 100%;">
      <source src="/images/movie2.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
    <figcaption>Figure 1: Fractal ISM interacting with a supernova-driven wind.</figcaption>
  </figure>
  
  <!-- Image -->
  <figure style="flex: 1;">
    <img src="/images/example_section.png" alt="wind_tunnel_sims" style="width: 100%;" />
    <figcaption>Figure 2: Turbulence in a wind with both hot and cold phases.</figcaption>
  </figure>
</div>



**Radiative Cooling and Magnetic Draping**

Although the positive impact of radiative cooling on cold cloud survival is well established, the combined role of magnetic fields remained unclear—previous work suggested magnetic draping could either prolong or curtail cloud lifetimes depending on the setup. We directly addressed this gap by running three-dimensional radiative MHD simulations to examine clouds in strongly magnetized galactic winds. Our findings reveal that ambient magnetic fields reduce the critical survival size by two orders of magnitude, enabling clouds smaller than 1 parsec to persist.

Magnetic draping forms a protective sheath that suppresses disruptive instabilities, and pairs with radiative cooling to extend lifetimes by at least a factor of ten over purely hydrodynamic or singly-cooled cases. The joint action not only boosts cloud acceleration (to several hundred km/s) but also maintains cloud integrity over multiple kiloparsecs, matching the distances and covering fractions observed in galaxy outflows. In essence, magnetic fields and cooling together enable robust cold cloud survival under conditions where prior theory was ambivalent.

<figure style="flex: 1;">
  <img src="/images/resized_example2.pdf" alt="ccsims with beta" style="width: 100%;" />
  <figcaption style="text-align: center !important;">Figure 2: SN-driven outflow interaction with different ISM configurations.</figcaption>
</figure>