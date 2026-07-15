# Robotic Dog - Mechanical Design Project

An initial mechanical design of a simple quadruped robotic dog, created using Tinkercad to apply core mechanical fundamentals for standing and walking.

## Project Steps

### 1. Body Design
A rectangular block body with a front sensor/camera cutout was modeled in Tinkercad.
- Full design bounding box: 95.3 x 95.3 x 61 mm
- Body height above legs: approximately 20 mm

### 2. Leg Design
The robot has 4 legs, each built from two segments connected at a joint (thigh and shin), designed once then duplicated and mirrored for symmetry.
- Shin diameter: approximately 6.4 mm
- Thigh diameter: approximately 13.3 mm
- Total leg length (ground to body attachment): approximately 40 mm

### 3. Degrees of Freedom
Each leg has 2 joints (Hip and Knee), giving a total of 8 DOF across all 4 legs.

### 4. Motor Selection
The MG996R servo motor was selected for its torque rating (10-11 kg.cm), low cost, and wide availability.

### 5. Torque Calculation
Based on the measured leg length (0.040 m) and a 0.3 kg load estimate, the required hip joint torque (with a 2x safety factor) is approximately 2.4 kg.cm, well within the MG996R's capacity.

### 6. Stability Analysis
The center of gravity must stay inside the support polygon formed by the ground-contact legs. With 4 legs down, the base is a stable rectangle; with 3 legs down (walking), it becomes a triangle.

### 7. Gait Selection
The Wave Gait was chosen, moving one leg at a time to prioritize stability over speed.

## Results

Screenshots of the design are included in this repository:

**Front / Isometric View**

![Front / Isometric View](front-iso-view.png)

**Rear View**

![Rear View](rear-view.png)

## Repository Contents

| File | Description |
|---|---|
| robot_dog_design.stl | 3D model exported from Tinkercad |
| front-iso-view.png | Front/isometric view screenshot |
| rear-view.png | Rear view screenshot |

## Tools Used
- Tinkercad (3D modeling and mechanical layout)
