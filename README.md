# Exoplanet-YauAward
Secondary Eclipse and Day-Night Modulation of Exoplanets Observed by Transiting Exoplanet Survey Satellite

![TESS](https://raw.githubusercontent.com/TabNahida/Exoplanet-YauAward/main/docs/image/sky_coverage.png)

## Introduction

This is my first exoplanet project which is introduced in the paper. In this project, I am trying to find secondary sclipse and day-night modulation of exoplanets from TESS's observation. Which this project did new is that I have made a fine process to analysis the TESS light curve by using python and matlib. By the fully developed program, we can easily analysis any TESS objects. In this repository, I have included my paper and the source code of my project.

## Abstract

Exoplanets have become a prominent area of research in astronomy. Since the discovery of the first solar-like star in 1995, astronomers have identified over 5000 extrasolar planets. These planetary systems exhibit a greater diversity compared to our solar system, offering valuable insights into the formation and evolution of planetary systems, as well as the potential for life in the Universe. To gain a deeper understanding of these exoplanets and their habitability, it is crucial to examine the composition of their atmospheres. Observation of the reflection of stellar radiation by the planetary atmosphere is a valuable approach to studying atmospheric properties. The Transiting Exoplanet Survey Satellite (TESS), delivering highly accurate photometric measurements with a precision of up to 0.001\%, can effectively detect the reflected light from exoplanets.

The planetary reflection can be detected by monitoring the light curve, which is usually the sum of the stellar flux and that of planetary reflection. During the secondary eclipse, the total light is that of the star alone. The difference therefore corresponds to the flux of the planet’s day-side region. An orbiting planet may also reveal its presence by the modulation of reflected starlight as the planet orbits its host star and shows day-night variation in the sight line of observers. The amplitude of flux variations due to secondary eclipse and day-night modulation is extremely small, at a level of 0.01\%, and very difficult to detect.

In this study, we develop an efficient Python program to search for the secondary eclipse and day-night modulation on the TESS light curves of over 400 known short-period transiting exoplanets. Our program can automatically identify and reject the low-quality photometric data points in light curves. The high-quality light curves are then folded in the orbital phase determined by the primary transits. The phase-folded average light curves have extremely high photometric precision, which is suitable for detecting the secondary eclipse and day-night modulation. As a result, we successfully identify planetary reflection in 17 transiting exoplanetary systems. The size of our sample is larger than the current TESS sample by twice. We also detect other important orbital-phase variations on the light curves in our sample, such as modulations due to the ellipsoidal effect and relativistic beaming effect. Our sample is valuable for the investigation of the planetary atmosphere, true mass, and orbital evolution. We plan to upgrade our Python program to search for orbital-phase modulation in non-transit exoplanets. Taking the advantage of high precision of TESS photometry, we expect to discover new exoplanets and determine the true masses of known exoplanets.

## Dependence

1. Python 3.8
2. Matlib (for plotting) 
3. Data from [TESS](https://tess.mit.edu)