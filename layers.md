---
layout: default
title: Software and Hardware layers
nav_order: 4
description: "An integrated digital ecosystem designed to proactively support mental wellbeing."
---

# *Hardware and Software Layers*

Buddi’s design relies on a *modular, multi-layered architecture* that separates *hardware sensing components* from *software intelligence*, ensuring *scalability, adaptability, and privacy-conscious design*. This separation also allows for *easy upgrades* or *extension with new devices or algorithms* without affecting the overall ecosystem.  

---

## **1. Hardware Layers**

The hardware layer is designed to *capture emotional, behavioral, and engagement data* in a *non-intrusive, classroom-friendly manner*.  

### **A. Ambient Sensors**
- *Purpose:* Detect subtle cues from students such as motion, posture, or environmental context.  
- *Examples:*
  - Desk-mounted *light & proximity sensors*  
  - Ambient *microphones* for noise-level monitoring (privacy-preserving)  
  - Optional *temperature, light, and CO₂ sensors* to monitor classroom comfort  
- *Role:* Feed *real-time context* to the Companion Intelligence Layer to enhance emotional inference.

### **B. Wearable Devices (Optional)**
- *Purpose:* Capture *physiological signals* linked to emotional states.  
- *Examples:*
  - Heart rate or pulse sensors  
  - Skin conductance / galvanic sensors  
  - Lightweight, wrist-worn or clip-on devices  
- *Role:* Provide *fine-grained, real-time affective data* for companion adaptation.

### **C. Student Interaction Devices**
- *Purpose:* Facilitate *direct engagement* with Buddi’s virtual companion and gamified modules.  
- *Examples:* 
  - Tablets, laptops, or interactive touchscreens  
  - Keyboards and mouse input for engagement tracking  
- *Role:* Deliver *micro-interventions, feedback, and gamified experiences*.

---

## **2. Software Layers**

The software layer is the *intelligent core of Buddi*, responsible for *emotion recognition, adaptive feedback, gamification, and classroom analytics*.  

### **A. Companion Intelligence Layer**
- *Components:*
  - *Emotion Recognition Engine:* Processes sensor input to infer emotional states.  
  - *Behavior Modeling Module:* Maintains dynamic profiles for adaptive responses.  
  - *Adaptive Response Generator:* Determines the *companion’s expressions, micro-interventions, and encouragement prompts*.  
- *Tech Stack:* Python / Node.js, TensorFlow Lite / PyTorch Mobile, REST/WebSocket APIs.

### **B. Intervention & Engagement Layer**
- *Components:*
  - *Calm Kit:* Sensory-friendly, ultra-short interventions (breathing exercises, doodling, grounding gestures).  
  - *Gamification Engine:* Soft progress visualizations, constellations, and reward loops.  
  - *Focus Trails:* Tracks engagement and transforms study patterns into *interactive visual feedback*.  
- *Role:* *Sustain engagement, promote self-regulation, and provide playful reinforcement.*

### **C. Data Aggregation & Analytics Layer**
- *Components:*
  - *EchoGarden:* Aggregates classroom mood data in *real-time*, anonymized for privacy.  
  - *Analytics Engine:* Generates trends, reports, and insights for educators.  
  - *Secure Storage:* Encrypts all data, ensuring *privacy and compliance*.  
- *Tech Stack:* PostgreSQL / Firebase, Python analytics libraries, D3.js / Plotly for visualizations.  

### **D. User Interaction Layer**
- *Components:* Frontend interface, mobile/tablet apps, dashboards.  
- *Tech Stack:* React Native / Flutter, Material Design, CSS/Sass for styling.  
- *Role:* Ensure *intuitive, accessible, and low-stimulation experiences* for neurodivergent learners.

---

## **3. Integration Between Hardware and Software**

- *Data Flow:* Sensor & interaction data → Companion Intelligence Layer → Intervention & Engagement → Analytics Layer → Feedback to user & educator dashboards.  
- *Local Processing:* Emotion recognition can occur *on-device*, minimizing latency and preserving privacy.  
- *Cloud/Server Support:* Aggregated, anonymized data stored for classroom insights, historical trends, and adaptive learning improvements.  

---

## **4. Key Design Principles**

1. *Non-Intrusive:* Sensors and wearables are optional and minimally invasive.  
2. *Scalable:* Modular hardware and software layers allow *easy addition of new sensors, interventions, or classrooms*.  
3. *Privacy-Focused:* Personal data never leaves the device unless anonymized for classroom analytics.  
4. *Adaptive:* Companion behavior, interventions, and gamification adapt over time based on *user engagement and emotional feedback*.  

---

*In summary*, the hardware and software layers of Buddi work in harmony to *create an emotionally intelligent, interactive, and privacy-conscious ecosystem* that supports *neurodivergent learners* and empowers educators with *actionable, anonymized insights*, all in a *playful and accessible environment*.

<style>
  .link-container {
    display: flex;
    justify-content: flex-end; /* aligns content to the right */
    padding: 20px;             /* optional spacing */
    background-color: #333;    /* dark background */
  }

  .right-link {
    color: white;               /* makes the link white */
    text-decoration: none;      /* removes underline */
  }

  /* optional hover effect */
  .right-link:hover {
    text-decoration: underline;
  }
</style>

<div class="link-container">
  <a href="workflow.html" class="right-link">Next : Workflows</a>
</div>