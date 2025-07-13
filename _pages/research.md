---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
math: true
---


**How do multiphase outflows emerge in realistic ISMs?**


***

Galaxies are vast systems composed of stars, gas, and dark matter — and their evolution is very puzzling. One reason is that feedback processes, where energy and matter flow out of galaxies in different phases, are not well understood and hard to study. These outflows start on small scales, but their combined effects can influence the galaxy on much larger scales, making the task of simulating these processes quite complex. The big question is how we can connect theoretical models with actual observations — that is, can we understand these processes, why they happen, and how they quantitatively affect galaxies and their surroundings?

Some of the first attempts try to look into why this happens by making the problem extremely simplified and focusing on one question at a time. We use these simplified, ideal simulations to be able to connect theory to the behaviour of these systems — predictions that we can then compare to observations. The latest advancements on the issue of these 'multiphase outflows' precisely follow this approach. The main issue with the coexistence of cold and hot gas in outflows is that supernovae, producing the hot outflow, should entrain cold material from its surroundings before leaving the galactic disk. We know this problem as the cloud-crushing issue and it has been a puzzle for a long time: 

<figure>
  <img src="/images/simple_multiplot_volweighted.png" alt="wind_tunnel_sims" />
  <figcaption>Figure 1: SN-driven outflow interaction with different ISM configurations.</figcaption>
</figure>

Picture a cloud of cold gas encountered by the wind. From instability theory, the destruction of this cloud, the cloud-crushing time \\( t_{cc} \\), will be much shorter than the time it takes to accelerate the cloud and entrain it by the hot wind, \\( t_{acc} \\) — for a gas of these temperatures, this is the equivalent of driving a firefighter's water hose blowing into the tube. So how can we entrain this cold phase? Gas in space also radiates energy away, which allows it to 'cool down'. If we have enough cooling strength, clouds can accrete some of the gas that would otherwise mix away during the interaction. This is, in other words, \\( t_\mathrm{cool,mix} < t_{cc} \\). This criterion gives us a critical size for cold clumps to survive the entrainment of the wind, \\( r_{crit} \\).

Cool! Theory can explain these outflows from spherical clouds of gas, so what is the issue? You can imagine the interstellar medium (ISM) looks nothing like single individual clumps, but rather arranges in filamentary and multicloud structures. So we looked into this by generating realistic gas distributions and driving a wind at speeds as high as 150 km/s through it. And we get a more complex scenario, where the total amount of cold gas \\( f_v \\), size of the ISM \\( L_{ISM} \\) and sizes of clumps \\( r \\) all play a role. Varying these three quantities can lead to different mass and velocity evolution for the cold phase, and interestingly, we see that this survival also emerges for certain values of \\( f_v \\) and \\( L_{ISM} \\) even if clumps are not bigger than the classical survival threshold, hinting that the evolution for complex systems is not properly described by it.

How can we understand the emergence of outflows? This is a statement about the effective depth of the ISM. In figure 2 we plot the total cold gas length perpendicular to the wind for each simulation, marking the existence or absence of cold gas in outflows, which gives us a distinct limit between crosses (absent) and circles (existent). This tells us that cold outflows will emerge universally under real galactic disks when:


$$
f_v \, L_{ISM} \geq r_{crit}
$$


which in turn means the outflows will emerge above ISM column densities: \\(N_H \geq 10^{18} \text{cm}^{-2}\\).

<figure style="text-align: center;">
  <img 
    src="/images/fvLism_plot_transparent.png" 
    alt="fvLism" 
    style="max-width: 60%; height: auto; margin: 0 auto; display: block;"
  />
  <figcaption style="text-align: center; font-style: italic; margin-top: 0.5em;">
    Figure 2: Emergence (dots) or destruction (cross) of multiphase outflows for ISM parameters.
  </figcaption>
</figure>


**Observing cold outflows**

What can the wind tell us about the structure of the original ISM? Absolutely nothing. We show that regardless of the initial distribution of clumps, clouds in the wind follow a Zipf's distribution (\\( dN/dm \propto m^{-2} \\)) shortly after the interaction with the wind. What is puzzling is that this law emerges universally in multiphase media, like the distribution of filaments in the ISM, but we do not exactly understand why.

The kinematics of outflows will show us that the phases of a multiphase wind are co-spatial and travelling at the same speeds. Both are profoundly coupled and develop turbulence only around the sound speed of cold gas. Turbulent motions for gas at \\( 10^4 \\) K are therefore transonic, whereas for the hot phase at \\( 10^6 \\) K, this is roughly equivalent to only \\( \sim 0.1 \\) % of its flow speed. Observations revealing highly turbulent X-ray emitting gas cannot purely arise from ISM interactions.

<div style="display: flex; justify-content: center; gap: 1rem; flex-wrap: wrap;">

  <figure style="flex: 1 1 45%; text-align: center;">
    <img src="/images/pdf_cdf_plot.png" alt="pdf" style="max-width: 100%; height: auto;" />
    <figcaption>Figure 3: Cump size probability density function (top) and cumulative distribution (bottom) for the cold phase.</figcaption>
  </figure>

  <figure style="flex: 1 1 45%; text-align: center;">
    <img src="/images/yavsh_vturb_cold_hot.png" alt="yavsh" style="max-width: 100%; height: auto;" />
    <figcaption>Figure 4: Turbulence of cold (left) and hot (right) gas in outflows as a function of time (shear timescale for wind to transverse ISM slab).</figcaption>
  </figure>

</div>

Simulations also prove that while maintaining a high areal covering fraction of cold gas, the volumetric filling fraction remains well below 1. This comes to explain the ubiquitousness of cold gas in outflows and their small relative sizes, from observations of the circumgalactic medium of galaxies through quasar absorption lines, showing the high percentage of cold gas detected but their low densities.

<figure>
  <img src="/images/vsf_3x3_subplots.png" alt="wind_tunnel_sims" />
  <figcaption>Figure 5: Velocity structure function of cold gas for 3 different simulations.</figcaption>
</figure>