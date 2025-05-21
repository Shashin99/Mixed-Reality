
# Mixed Reality Warzone AR Application

## Project Title

**Mixed Reality Assignment – Group ID: 55**  
**Course:** Current Trends in Software Engineering (SE4010)  
**Degree:** B.Sc. (Hons) in Information Technology Specializing in Software Engineering  
**Institute:** Sri Lanka Institute of Information Technology (SLIIT)  
**Date:** May 2025

---

## Table of Contents

1. [Project Overview](#project-overview)  
2. [Scenario](#scenario)  
3. [Development Process](#development-process)  
   - [Tools](#tools)  
   - [Technologies](#technologies)  
   - [Steps Followed](#steps-followed)  
4. [Implementation](#implementation)  
5. [Creative Features](#creative-features)  
6. [Conclusion](#conclusion)  
7. [Team Members and Contributions](#team-members-and-contributions)  
8. [Demo](#demo)  
9. [Repository](#repository)

---

## Project Overview

This project presents the development of a mixed reality (MR) application designed to immerse users in a dynamic warzone scenario, commemorating the victory over LTTE. The AR experience simulates a high-intensity battlefield where a soldier jumps from a helicopter to intercept a moving armored jeep, surrounded by tanks and a BRDM.

Using marker-based technology, the application integrates 3D animated models rendered in real time through a mobile webcam, offering an interactive and realistic augmented reality experience.

---

## Scenario

The chosen AR scenery is a battlefield designed for immersive experience with the following features:

- A helicopter rotating in a fixed position
- Soldiers jumping from the helicopter
- A moving armored jeep, two tanks, and a BRDM (armored reconnaissance vehicle)
- Animated elements with synchronized sound effects
- A thematic warzone background for realism

---

## Development Process

### Tools

- Visual Studio Code (VS Code)
- Google Chrome / Safari (for testing)

### Technologies

- A-Frame
- AR.js
- HTML5
- JavaScript
- GLB (GL Transmission Format for 3D models)

### Steps Followed

1. **Marker Setup**  
   - Used the HIRO marker from AR.js for tracking.

2. **Model Integration**  
   - Imported `.glb` models and positioned/scaled them properly.

3. **Animations**  
   - Added movement to tanks, jeep, BRDM, helicopter, and jump animation for the soldier.

4. **Sound Integration**  
   - Used `<a-sound>` component for spatial, looping sound effects.

5. **Background Layout**  
   - Added textures, rocks, and trees to enhance scene depth.

6. **Testing and Deployment**  
   - Hosted using `ws`, tested via webcam and marker placement.

---

## Implementation

**Folder Structure:**

```
/Mixed-Reality
│
├── assets/          # Textures, sound effects
   ├── models/          # GLB models for all 3D assets
├── index.html       # Main HTML file with A-Frame scene
```

To run the app:

```bash
git clone https://github.com/Shashin99/Mixed-Reality.git
cd Mixed-Reality
npm install -g ws
ws
# Visit http://localhost:8000 and use webcam with HIRO marker
```

---

## Creative Features

- **Animations**  
  Real-time animations include rotating helicopters, moving vehicles, and jumping soldiers.

- **Sound Integration**  
  Each object is paired with a spatial sound: engine hums, helicopter blades, battle noise.

- **Realistic Scene Composition**  
  Models are scaled and placed accurately with immersive layout and environment models.

---

## Conclusion

This project highlights the power of marker-based AR using A-Frame and AR.js. It merges dynamic animations, immersive sound, and interactive features to simulate a warzone. Through this, we gained hands-on experience in:

- Web-based AR development
- 3D model manipulation
- Animation and sound integration
- Marker tracking and camera testing

The final result is a real-time, browser-based AR experience that is both educational and immersive.

---

## Team Members and Contributions

| Name                      | Reg. Number | Email                       | Contact     | Contribution                                                                                                                         |
|---------------------------|-------------|------------------------------|-------------|--------------------------------------------------------------------------------------------------------------------------------------|
| **Wimaladharma T. H. Y. B.** | IT21378270  | it21378270@my.sliit.lk      | 0763362177  | Imported BRDM models, implemented animations, embedded sound effects, designed layout, and created final report                     |
| **Hanshani S. G. H. S**      | IT21377358  | it21377358@my.sliit.lk      | 0765403380  | Imported Jeep models, implemented animations, embedded sound effects, designed layout, and created final report                     |
| **Kalpajith K. L. S**        | IT21355196  | it21355196@my.sliit.lk      | 0768477437  | Imported helicopter and soldier models, implemented animations, embedded sound effects, designed layout, and created final report   |
| **De Silva K. P. C.**        | IT21356018  | it21356018@my.sliit.lk      | 0719513764  | Imported tank models, implemented animations, embedded sound effects, designed layout, and created final report                     |

---

## Demo

🎥 **Video Demonstration**  
[Watch Here](https://drive.google.com/file/d/1wA8oizB9lXEEFthYqGHKYvNew9VwTVhR/view?usp=sharing)

---

## Repository

📂 **GitHub Repository**  
[GitHub - Mixed Reality Project](https://github.com/Shashin99/Mixed-Reality.git)

---

© 2025 | Department of Software Engineering | Sri Lanka Institute of Information Technology
