# Cools Transmissive Self-Aligned Annealing

## Stop heating the surface. Activate the buried target directly.

> **Conventional laser annealing heats where the beam first lands and waits for heat to diffuse toward the target.**  
> **Cools sends sub-bandgap light through the semiconductor body and generates heat at the backside contact, implanted layer or buried semiconductor region that actually requires activation.**

[한국어](README_KR.md) · [中文](README_ZH.md)

---

## The strategic proposition

Cools proposes a material-neutral annealing platform for advanced semiconductor and power-device fabrication.

This is not another surface laser anneal.  
It is not a dual-beam carrier-generation scheme.  
It is not a preheat-assisted thermal diffusion process.

> **The semiconductor becomes the optical window. The buried target becomes the heater.**

```text
Sub-bandgap optical pulse
→ transmitted through the semiconductor body
→ selectively absorbed by the backside metal, doped layer or damaged region
→ heat peak self-aligns to the required activation zone
→ front-side device remains below its thermal-damage limit
```

The optical absorption profile itself determines where heating occurs. No separate optical alignment to the buried interface is required once the material stack is designed.

---

## Why the industry needs this architecture

Vertical devices require high-temperature reactions at the backside after the front-side gate, source, emitter and wiring structures may already be complete.

Conventional processing creates a fundamental conflict:

```text
Higher backside activation temperature
→ better ohmic contact or dopant activation
→ greater heat diffusion toward the finished front side
→ higher risk of gate, dielectric and metal damage
```

Cools breaks that conflict by separating the optical entrance surface from the thermal target surface.

> **The wafer thickness becomes an optical transmission path and a thermal buffer distance—not merely material to be heated.**

---

## Core operating principle

### TRANSMIT

Choose light with photon energy below the semiconductor bandgap so that band-to-band absorption in the semiconductor body is suppressed.

### SELECT

Use a backside contact-forming layer, heavily doped region, implantation-damaged region or defect-rich region that absorbs more strongly than the surrounding semiconductor.

### SELF-ALIGN

The location of dominant absorption becomes the location of dominant heating. The material stack, doping profile or damage profile defines the activation zone.

### CONTAIN

Control pulse width so that thermal diffusion remains localized near the target interface. In SOI structures, the Buried Oxide (BOX) additionally acts as a low-absorption optical boundary and a thermal-insulation boundary.

### ACTIVATE

Form or activate the backside ohmic contact, field-stop layer, collector layer or upper semiconductor layer while suppressing thermal damage to the already completed device structure.

---

## One optical platform across multiple semiconductor materials

The patent portfolio covers a common architecture across:

- Silicon (Si) vertical IGBT backside activation;
- Silicon Carbide (SiC) backside ohmic-contact formation;
- Gallium Nitride (GaN) backside ohmic-contact formation;
- Gallium Oxide (Ga₂O₃) backside ohmic-contact formation;
- material-neutral backside contact annealing; and
- SOI upper-layer self-aligned annealing using BOX optical and thermal confinement.

> **One optical concept. Multiple semiconductor materials. Heat generated only where activation is required.**

---

## Silicon IGBT: the implant profile becomes its own annealing mask

For a vertical Insulated Gate Bipolar Transistor (IGBT), sub-bandgap light passes through the low-doped drift region and is absorbed preferentially in the heavily doped or implantation-damaged field-stop and collector regions.

Representative absorption mechanisms include:

- Free-Carrier Absorption (FCA);
- implantation-damage absorption;
- defect-state absorption;
- dopant-related absorption; and
- temperature-enhanced absorption.

```text
Low-doped drift layer: optical transmission and thermal buffering
Heavily doped / damaged backside layer: selective absorption and activation
```

The doping and damage profile therefore self-aligns the activation depth without relying only on heat diffusion from the wafer surface.

---

## SiC: form the high-temperature contact chemistry without a high-temperature front-side cycle

Vertical SiC devices require high-temperature backside contact reactions, commonly involving silicide or carbide formation.

Cools transmits near-infrared or short-wave infrared light through the SiC body and concentrates absorption in the backside contact-forming layer or its interface.

The platform targets the simultaneous requirements of:

- high local contact-reaction temperature;
- low front-side thermal exposure;
- thin-substrate compatibility;
- reduced substrate resistance; and
- reduced backside contact resistance.

> **Create the heat peak at the SiC contact interface—not at the optical entrance surface.**

---

## GaN: use the wide-bandgap body as an optical window

In vertical GaN devices, sub-bandgap light can traverse a free-standing GaN substrate and be absorbed by the backside contact-forming metal stack.

The GaN body is used as the main transmission path, while the metal or metal–GaN reaction region becomes the thermal target.

For GaN-on-Si structures, the portfolio also covers handle-substrate removal or optical/absorption matching that preserves dominant heating at the backside contact region.

> **The GaN substrate becomes the optical window, not the heat source.**

---

## Ga₂O₃: optical transparency plus thermal confinement

Gallium Oxide combines an ultra-wide bandgap with low thermal diffusivity.

In the Cools architecture:

- the Ga₂O₃ body transmits the sub-bandgap activation light;
- the backside contact-forming layer absorbs and heats;
- low thermal diffusivity suppresses heat penetration toward the front-side device; and
- crystal-orientation-dependent optical and thermal anisotropy becomes a process-design variable.

> **Ga₂O₃ does not merely transmit the light. It helps confine the heat at the backside contact.**

---

## SOI: the BOX layer becomes an annealing cage

In a Silicon-On-Insulator (SOI) structure, the Buried Oxide (BOX) is used as more than an electrical isolation layer.

It performs two active process functions:

- **optical boundary:** relatively low absorption at the selected wavelength;
- **thermal boundary:** low thermal conductivity that suppresses heat flow into the handle substrate.

The upper semiconductor layer absorbs more strongly than the BOX, while the BOX confines the generated heat in the upper layer.

> **The BOX defines where the optical absorption stops and where the thermal activation stays.**

This supports selective upper-layer annealing in thin films and three-dimensional integrated structures without requiring a separate carrier-generation beam or preheating beam.

---

## Conventional approach versus Cools

| Process dimension | Conventional surface or dual-beam annealing | Cools transmissive self-aligned annealing |
|---|---|---|
| Optical entry | Same side as the heated surface | Opposite side or transmissive path |
| Main absorption | First illuminated surface | Backside contact, doped layer or damaged region |
| Heat placement | Determined mainly by surface absorption and diffusion | Determined by material, doping and damage selectivity |
| Alignment | Optical positioning and surface geometry | Material-stack self-alignment |
| Front-side protection | More difficult as wafer is thinned | Pulse-controlled thermal separation |
| Optical system | Excimer, green, preheat or dual-beam options | Single sub-bandgap pulse or pulse train can initiate heating |
| Material range | Frequently optimized material by material | Common Si / SiC / GaN / Ga₂O₃ / SOI architecture |
| Functional layer | Additional absorber may be required | Existing barrier or contact layer can also act as absorber |

---

## Fab and device-manufacturer value

The platform is intended to enable:

- lower thermal budget after front-side completion;
- backside contact formation on thinner substrates;
- improved vertical-device on-resistance through substrate thinning and lower contact resistance;
- reduced front-side gate, dielectric and metallization damage;
- simpler optical equipment than carrier-generation plus heating-beam architectures;
- common equipment architecture across multiple semiconductor materials; and
- activation depth controlled by absorption profile and pulse duration rather than surface diffusion alone.

> **Do not carry heat through the wafer. Carry light through the wafer and create heat at the target.**

---

## Patent portfolio

The patent-pending portfolio includes:

- doping- and damage-profile-based self-aligned backside activation for Si IGBT;
- BOX-confined self-aligned annealing of SOI upper semiconductor layers;
- material-neutral backside contact self-aligned annealing;
- Ga₂O₃ transmissive backside contact annealing with low-thermal-diffusivity confinement;
- GaN transmissive backside ohmic-contact formation; and
- SiC transmissive backside ohmic-contact formation.

The portfolio also covers resulting device structures with localized reaction, activation or heat-affected profiles concentrated at the target interface and reduced toward the opposite device surface.

---

## Adoption message

> **The next generation of backside activation should not be built around stronger surface heating.**  
> **It should be built around optical transmission, selective absorption and interface-level heat generation.**

Cools is seeking technical evaluation, joint process development and qualification with semiconductor manufacturers, power-device companies and annealing-equipment partners.

---

## Patent protection and transaction options

The technologies and architectures described in this repository are protected by pending patent applications and associated proprietary know-how of Cools Inc.

Potential transaction structures may include:

- exclusive or non-exclusive patent licensing;
- material-, device-, node- or territory-limited rights;
- joint process development and qualification;
- optical equipment and fab integration;
- strategic investment or transfer of the relevant technology business; and
- where commercially appropriate, assignment or transfer of the relevant patent applications and patent rights themselves.

**Negotiations are not limited to a licence. Where the strategic purpose and conditions are appropriate, the relevant patent portfolio itself may be included in the transaction.**

Publication of this repository does not constitute a licence, waiver or permission to practise the technology. Detailed optical parameters, layer stacks, thermal windows, process integration flows and claim charts are reserved for controlled technical and legal discussions.

---

## Contact

**Cools Inc.**  
Jinhyun Cho  
Former Samsung Electronics Master-level semiconductor engineer  
Ph.D., Mechanical Engineering, University of Michigan

Email: jhcho@cools.co.kr  
Email: jhcho9494@naver.com  
Mobile: +82-10-2280-9414
