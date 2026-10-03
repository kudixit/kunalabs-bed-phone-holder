# KunaLab Articulated Bed Phone Holder

A bed-mounted, multi-axis articulated phone holder designed and prototyped
from scratch using Fusion 360 and FDM 3D printing.

The project has progressed through two functional prototypes, with V2
incorporating lessons learned from mechanical testing of the original design.

<!-- Replace with final V2 image -->
<img width="1858" height="1240" alt="V2 Landscape View" src="https://github.com/user-attachments/assets/4afb13d9-e8ae-488f-839d-3618a789d92d" />


## The Problem

I wanted a phone holder that could mount directly to my bed frame, extend to
a comfortable viewing position, and be repositioned in multiple axes without
requiring a fixed stand or handheld device.

The design needed to:

- Clamp securely to the bed frame
- Provide substantial reach
- Allow multiple rotational degrees of freedom
- Be adjustable by hand
- Lock its position under the weight of a smartphone
- Be manufacturable primarily through FDM 3D printing

---

## V1 — Proof of Concept

V1 was designed in Fusion 360 and printed primarily in PLA.

The mechanism consisted of:

- Bed-frame clamp
- Two articulated arms
- Two primary friction-lock pivots
- Adjustable phone orientation mechanism
- Printed threaded hardware
- Rubber friction interfaces

<img width="1858" height="1240" alt="V1 Assembly" src="https://github.com/user-attachments/assets/76922aee-75df-4d6d-9480-6bedabb7d6bc" />
<img width="1858" height="1240" alt="V1 Assembly" src="https://github.com/user-attachments/assets/c41069b2-6c20-4096-8c5a-d7393db46d5d" />
<img width="1858" height="1240" alt="V1 Assembly" src="https://github.com/user-attachments/assets/07bf418a-e3ed-437b-8ad0-667666c824e9" />
<img width="1858" height="1240" alt="V1 Assembly" src="https://github.com/user-attachments/assets/9e648fe6-9b0c-4de7-bef1-ccb04d336927" />

### V1 Result

V1 successfully demonstrated the overall mechanical concept.

The completed assembly was able to:

- Clamp securely to the bed
- Support a smartphone
- Hold multiple viewing positions
- Provide the intended articulation and reach
- Allow manual positioning through friction-lock pivots

However, extended testing revealed limitations in the original pivot design,
particularly when the arm was placed in high-moment positions.

---

## V1 Testing & Lessons Learned

### Pivot Friction

The original PLA-on-PLA pivot surfaces did not provide enough friction in
high-moment positions.

Adding thin rubber friction washers substantially increased the available
holding torque and demonstrated that the pivot geometry itself was viable.

### Printed Thread Clearance

Several printed thread clearances were tested during development.

For the M8 printed interfaces used in V1, approximately **0.30 mm radial
clearance** on the female threads produced a usable fit on my printer.

A **0.75 mm entrance chamfer** was also added to the male and female threaded
interfaces to improve thread engagement.

### Pivot 1 Failure

During extended testing, the printed screw at the first pivot fractured.

Pivot 1 experiences the largest bending moment because it supports the
complete downstream arm assembly and smartphone.

The failure identified the printed fastener as a structural limitation rather
than a failure of the overall articulated-arm concept.

<img width="3024" height="4032" alt="V1 Pivot 1 Failure" src="https://github.com/user-attachments/assets/2b77393c-fade-4a1c-8901-6336aa33a9ae" />

This failure became the primary design input for V2.

---

# V2 — Metal Pivot & Friction-Lock Redesign

V2 preserves the successful geometry and articulation of V1 while redesigning
the primary pivots for greater strength, holding torque, and durability.

The major change was separating the functions of the printed and metal
components.

Instead of using the printed hardware as the structural fastener, V2 uses
metal hardware to carry the pivot clamping load while the printed components
provide geometry, alignment, and ergonomic adjustment.

## V2 Improvements

The redesigned system incorporates:

- M8 steel pivot bolts
- Captive M8 steel nuts
- 3D-printed star adjustment knobs
- Steel flat washers for load distribution
- Neoprene friction washers on both sides of each primary pivot
- Press-fit hex pockets for captured bolt heads and nuts
- Improved mechanical strength at the highest-load pivots
- Improved grip and adjustment ergonomics

<!-- Add photo of Home Depot / V2 hardware here -->
<img width="3024" height="4032" alt="Metric Hex Nut" src="https://github.com/user-attachments/assets/5d7bbbc7-29a4-453f-b927-21f30e1e7786" />
<img width="3024" height="4032" alt="Metric Hex Head Screw" src="https://github.com/user-attachments/assets/a5956e27-c645-4d72-82c7-6901a377c31a" />
<img width="4032" height="3024" alt="Rubber Washer" src="https://github.com/user-attachments/assets/b7f11c77-674f-499a-a426-be01d14a9fdb" />


## Captive Star Knobs

Custom star knobs were designed to capture the M8 bolt head and nut while
allowing the structural load to remain on standard metal hardware.

The hex pockets were tuned through physical fit testing rather than relying
only on nominal hardware dimensions.

The final nut pocket was designed at approximately **12.8 mm across flats**,
producing a light press fit that prevents the nut from rotating or falling
out of the knob.

The star-shaped geometry also provides substantially better hand grip than
the original round adjustment knobs.
<img width="1858" height="1240" alt="V2 Landscape View" src="https://github.com/user-attachments/assets/45fc5241-163c-4bb5-8461-c1b06529f5fa" />


## V2 Pivot Stack

Each primary pivot uses the following mechanical stack:

**Star knob + captured M8 bolt head**  
↓  
**Steel flat washer**  
↓  
**Outer arm**  
↓  
**Neoprene friction washer**  
↓  
**Center pivot block**  
↓  
**Neoprene friction washer**  
↓  
**Outer arm**  
↓  
**Steel flat washer**  
↓  
**Captured M8 nut + star knob**

The steel washers distribute clamping force across the printed components,
while the internal neoprene washers generate friction at the rotating
interfaces.

This allows the pivots to remain continuously adjustable while still
developing enough holding torque to support the extended arm and smartphone.

---

## V2 Validation

V2 was assembled and tested with the smartphone installed under real-use
conditions.

Testing included extended arm positions that generate significantly higher
moments at the primary pivots.

The redesigned pivot system has remained secure during continued use with
no observed pivot fastener failure and substantially improved resistance
to slipping compared with V1.

The holder can be loosened for repositioning and manually tightened to
securely maintain the desired viewing position.

<!-- Replace with final real-life V2 photo -->
<img width="1858" height="1240" alt="V2 Landscape View" src="https://github.com/user-attachments/assets/8ad5041d-9a26-4c21-85f0-10330381b909" />


---

## Design Evolution

The development process followed a simple iterative engineering cycle:

**Design → Prototype → Test → Identify Failure → Redesign → Validate**

V1 established that the overall articulated-arm geometry and friction-lock
concept worked.

Testing then exposed the limitations of using printed fasteners at the
highest-load pivot.

V2 addressed that failure by transferring the structural load to standard
metal hardware while retaining 3D-printed components for the custom geometry
and user interface.

---

## Future Development

Potential future development includes:

- Further weight and geometry optimization
- Improved cable management
- Additional ergonomic refinement
- Motorized articulation
- Electronic position control
- Automated positioning of the primary arm pivots

---

## Tools & Materials

### Design / Manufacturing

- Autodesk Fusion 360
- Bambu Studio
- FDM 3D printing

### Materials / Hardware

- PLA
- M8 steel bolts
- M8 steel nuts
- Steel flat washers
- Neoprene friction washers

---

## Project Files

Design files, printable components, and development images are organized by
revision:

- `V1/` — Original proof-of-concept design and testing
- `V2/` — Metal-pivot redesign and validated prototype
