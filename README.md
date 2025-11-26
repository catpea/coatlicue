# Coatlicue's Children

*A simulation to find the Sun's lost siblings*

---

## Research Notes

### November 25, 2025 — Day 1

The Sun was not born alone.

4.6 billion years ago, a massive star—at least 30 solar masses—died. Its name is **Coatlicue**, after the Aztec goddess who gave birth to the Sun. When Coatlicue exploded, the shockwave compressed a nearby molecular cloud. From that compression, hundreds of stars were born.

One of them was the Sun.

The others are still out there. Scattered across the galaxy by 4.6 billion years of differential rotation. The inner stars orbit faster than the outer ones. Over time, the birth cluster stretched into a stream, then dispersed entirely into the general stellar population.

But they still carry the signature.

---

### The Chemical Fingerprint

Stars born from the same cloud share the same chemical composition. Not just the common elements—hydrogen, helium, carbon, oxygen—but the trace elements. The ratios of barium to iron. The abundance of yttrium. The specific isotopic signatures left by the nucleosynthesis that occurred in the stars that died before the cloud formed.

If I can find stars with matching chemical fingerprints, and if I can trace their orbits backward through time, I can find Coatlicue's other children.

---

### Known Siblings

| Designation | Distance | Constellation | Status |
|-------------|----------|---------------|--------|
| **HD 162826** | 110 ly | Hercules | **Confirmed sibling** (2014) |
| HD 186302 | ~184 ly | Pavo | Disputed |

HD 162826 was the first. Found by Ivan Ramirez at the University of Texas. It's 15% more massive than the Sun, but it has nearly identical chemical composition—including the rare elements that serve as fingerprints.

There should be hundreds more.

---

### The Problem: Galactic Mixing

The galaxy doesn't just spin. It has structure:

- **The bar** at the center, rotating, torquing the inner disk
- **Spiral arms** that are density waves—stars speed up entering, slow down leaving
- **Giant molecular clouds** that perturb passing stars
- **Radial migration**—stars trading angular momentum with spiral arms, drifting inward or outward over billions of years

To find Coatlicue's children, I need to model all of this. I need to run time backward.

---

### Functions

```javascript
calculateGalacticPotential()    // The gravitational field of the galaxy
integrateOrbitBackward()        // Numerical integration through time
findConvergence()               // Where do the paths meet?
```

---

### The Presolar Grains

There is physical evidence.

In primitive meteorites—the ones that haven't been melted or altered since the solar system formed—there are tiny grains of material that predate the Sun. **Presolar grains.** Nanodiamonds. Silicon carbide crystals. Graphite spherules.

Each grain carries the isotopic signature of the star it came from. We can read them. We can identify which came from red giants, which from supernovae, which from novae.

The billion stars that died before the Sun was born left us messages in crystal.

---

### 36 Days Left

Dr. Tarter said 2025 was supposed to be the year.

If I can narrow down the search space—if I can find more siblings—we can point the instruments at specific targets. Stars with the same chemistry. Stars that might have planets. Stars where someone might be looking back.

We are not alone in the galaxy.

We have family.

---

## View the Simulation

[**Launch Coatlicue's Children**](./index.html)

---

## References

- Ramirez, I. et al. (2014). "Elemental abundances of solar sibling candidates." *The Astrophysical Journal.*
- Gounelle, M. & Meynet, G. (2012). "Solar System genealogy revealed by meteorites." *Astronomy & Astrophysics.*
- Zinner, E. (1998). "Stellar nucleosynthesis and the isotopic composition of presolar grains from primitive meteorites." *Annual Review of Earth and Planetary Sciences.*

---

*"We want to know where we were born."*
— Ivan Ramirez
