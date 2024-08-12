# VSD-Custom-Layout-Course
This repository provides a comprehensive summary of the VSD Custom Layout Course. It covers essential topics such as CMOS process steps, design rule checks, and practical lab activities.
## Table of Contents

1. [Introduction](#introduction)
2. [Module 1 - 16 Mask CMOS Process](#module-1---16-mask-cmos-process)
   - [Step 1: Selecting a Substrate](#step-1-selecting-a-substrate)
   - [Step 2: Creating Active Regions for Transistors](#step-2-creating-active-regions-for-transistors)
   - [Step 3: N-Well and P-Well Formation](#step-3-n-well-and-p-well-formation)
   - [Step 4: Formation of Gate](#step-4-formation-of-gate)
   - [Step 5: Lightly Doped Drain (LDD) Formation](#step-5-lightly-doped-drain-ldd-formation)
   - [Step 6: Source and Drain Formation](#step-6-source-and-drain-formation)
   - [Step 7: Contacts and Interconnects](#step-7-contacts-and-interconnects)
   - [Step 8: High-Level Metal Formation](#step-8-high-level-metal-formation)
3. [Additional Resources](#Additional_Resources)

---

## Introduction

This repository documents the hands-on lab activities and theoretical concepts covered in the VSD Custom-Layout course. The course is designed to teach the fundamentals of CMOS layout design using a 16-mask process. It includes various modules that guide learners through the steps of creating CMOS structures, extracting circuits, performing design rule checks, and simulating pre-layout and post-layout circuits.

---

## Module 1 - 16 Mask CMOS Process

### Step 1: Selecting a Substrate

- **Objective:** Select a P-type substrate with a resistivity of 5-50 ohms and maintain a doping level lower than that of the well (~10^15 cm^-3).
- **Process:** The substrate is chosen based on the required electrical properties, ensuring it meets the resistivity and doping criteria.
- **Outcome:** A suitable P-type substrate is selected for the CMOS fabrication process.

### Step 2: Creating Active Regions for Transistors

- **Objective:** Define the active regions for transistors by using LOCOS (Local Oxidation of Silicon).
- **Process:**
  1. Deposit a 40nm layer of SiO2 on the substrate.
  2. Deposit 80nm of Si3N4 and 1um of photoresist.
  3. Apply Mask1 and expose the photoresist to UV light.
  4. Perform LOCOS to oxidize the exposed regions, forming isolation bumps.
  5. Remove the Si3N4 layer using hot phosphoric acid.
- **Outcome:** The active regions are defined, and isolation bumps are formed to separate transistor areas.

### Step 3: N-Well and P-Well Formation

- **Objective:** Create N-well and P-well regions for NMOS and PMOS transistors.
- **Process:**
  1. Apply photoresist on the intended N-well region.
  2. Perform ion implantation with P-type Boron ions to create the P-well.
  3. Similarly, create the N-well using N-type ions.
  4. Diffuse the wells to form well-defined regions.
- **Outcome:** N-well and P-well regions are successfully created.

### Step 4: Formation of Gate

- **Objective:** Form the gate, the most critical terminal of a MOSFET.
- **Process:**
  1. Apply photoresist and perform low-energy Boron implantation for threshold voltage adjustment.
  2. Etch the original oxide layer and regrow a high-quality oxide (~10nm thin).
  3. Deposit a polysilicon layer (~0.4um) and dope it with N-type impurity.
  4. Use Mask6 to define the gate layer.
- **Outcome:** The gate structure is formed with precise control over the threshold voltage.

### Step 5: Lightly Doped Drain (LDD) Formation

- **Objective:** Form LDD regions to reduce electric field intensity at the drain and source junctions.
- **Process:**
  1. Apply Mask7 and perform N-type ion implantation on the P-well side.
  2. Apply Mask8 and perform P-type ion implantation on the N-well side.
- **Outcome:** LDD regions are successfully formed.

### Step 6: Source and Drain Formation

- **Objective:** Form the source and drain regions of the transistors.
- **Process:**
  1. Apply a screen oxide layer to prevent channeling.
  2. Perform N+ implantation on the P-well side using Mask9.
  3. Perform P+ implantation on the N-well side using Mask10.
  4. Anneal the wafer at high temperature to extend the source and drain profiles.
- **Outcome:** The source and drain regions are formed and annealed for stability.

### Step 7: Contacts and Interconnects

- **Objective:** Form contacts and interconnects for local connections.
- **Process:**
  1. Etch the oxide layer and deposit a titanium layer using sputtering.
  2. Heat the wafer to form a TiN layer.
  3. Use Mask11 to define and clean the TiN layer.
- **Outcome:** Contacts and interconnects are formed for local circuit connections.

### Step 8: High-Level Metal Formation

- **Objective:** Form high-level metal layers for robust interconnections.
- **Process:**
  1. Deposit SiO2 doped with phosphorus or boron and polish the surface.
  2. Use Mask12 to drill contact holes and deposit a TiN layer.
  3. Perform chemical mechanical polishing and deposit an aluminum layer.
  4. Use Mask13 to etch the aluminum layer and form interconnections.
- **Outcome:** High-level metal interconnections are formed, completing the CMOS structure.

---



## Additional Resources
- **References:** Books and articles on CMOS processes and VLSI design.
