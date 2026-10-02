# KunaLab Articulated Bed Phone Holder

A bed-mounted, multi-axis articulated phone holder designed and prototyped
from scratch using Fusion 360 and FDM 3D printing.

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

## V1

V1 was designed in Fusion 360 and printed primarily in PLA.

The mechanism consists of:

- Bed-frame clamp
- Two articulated arms
- Two primary friction-lock pivots
- Adjustable phone orientation mechanism
- Printed threaded hardware
- Rubber friction interfaces

<img width="1858" height="1240" alt="Photo on 10-2-26 at 11 06 AM" src="https://github.com/user-attachments/assets/76922aee-75df-4d6d-9480-6bedabb7d6bc" />
<img width="1858" height="1240" alt="Photo on 10-2-26 at 11 04 AM" src="https://github.com/user-attachments/assets/c41069b2-6c20-4096-8c5a-d7393db46d5d" />
<img width="1858" height="1240" alt="Photo on 10-2-26 at 11 11 AM" src="https://github.com/user-attachments/assets/07bf418a-e3ed-437b-8ad0-667666c824e9" />
<img width="1858" height="1240" alt="Photo on 10-2-26 at 11 09 AM" src="https://github.com/user-attachments/assets/9e648fe6-9b0c-4de7-bef1-ccb04d336927" />

## V1 Result

V1 successfully demonstrated the overall concept.

The completed assembly was able to:

- Clamp to the bed
- Support a smartphone
- Hold multiple viewing positions
- Provide the intended articulation and reach

Rubber washers added to the pivot interfaces significantly increased the
available holding friction.

## What I Learned

### Pivot friction

The original PLA-on-PLA pivot surfaces did not provide enough friction in
high-moment positions.

Adding thin rubber friction washers substantially increased holding torque.

### Thread clearance

Several printed thread clearances were tested during development.

For the M8 printed interfaces used in V1, approximately 0.30 mm radial
clearance provided a usable fit on my printer for the femaile threads. Also added 0.75 mm chamfer for both male and female entrance of threads.

### Pivot 1 failure

During extended testing, the printed screw at the first pivot fractured.

Pivot 1 experiences the largest moment because it supports the complete
downstream arm assembly and smartphone.

This identified the printed fastener as a structural limitation rather than
the overall articulated-arm concept.

<img width="3024" height="4032" alt="IMG_3523" src="https://github.com/user-attachments/assets/2b77393c-fade-4a1c-8901-6336aa33a9ae" />

## V2 Development

Planned improvements include:

- Metal M8 pivot bolts
- Captive metal M8 nuts
- 3D-printed star knobs surrounding the metal hardware
- Flat load-distribution washers
- Rubber friction washers on both pivot interfaces
- Increased pivot durability
- Improved ergonomics
- Refinement of the phone rotation mechanism

The goal of V2 is to preserve the successful V1 geometry while improving
holding torque, durability, and ease of adjustment.

## Tools

- Fusion 360
- Bambu Studio
- FDM 3D printing
- PLA
