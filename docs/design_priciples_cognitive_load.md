# Cognitive Load–Aware Design Principles

This document outlines design principles derived from cognitive psychology that guide the interface decisions in this project. Each principle links human cognitive limitations to concrete interface design choices.

---

## Principle 1: Minimize Extraneous Cognitive Load

### Psychological Basis
Working memory has a limited capacity of approximately four meaningful chunks at a time.  
Extraneous cognitive load consumes these limited resources without contributing to task completion, leading to fatigue, stress, and disengagement.

### Interface Problems
- Too many buttons or actions visible simultaneously  
- Visually unstable content that frequently changes  
- Competing animations and information streams  

### Application in This Project
- Instagram overloads users with multiple simultaneous affordances (like, comment, share, follow).
- Spotify overlays listening with visual stimulation such as animations and recommendations.

### Design Rule
An interface should expose **only task-relevant information at each step**.

### Wireframe Implications
- Fewer visible actions per screen  
- Progressive disclosure instead of all-at-once controls  

---

## Principle 2: Respect Attentional Limits

### Psychological Basis
Attention is finite and fragile.  
Sustained attention requires recovery periods, and continuous attentional capture leads to attentional collapse and mental fatigue.

### Interface Problems
- Infinite scroll  
- Lack of completion signals  
- Absence of rest states  

### Application in This Project
- Instagram late-night scrolling forces sustained attention without recovery.
- Spotify autoplay maintains engagement without clear pause cues.

### Design Rule
Interfaces must **signal completion, rest, or transition points**.

### Wireframe Implications
- Natural stopping points  
- Explicit “pause” or “you’re done” moments  
- Clear session boundaries  

---

## Principle 3: Reduce Prediction and Monitoring Load

### Psychological Basis
The brain constantly predicts what will happen next.  
Uncertainty increases cognitive effort, and continuous monitoring drains working memory resources.

### Interface Problems
- Algorithmic unpredictability  
- Hidden navigation paths  
- Gesture based ambiguity  

### Application in This Project
- Spotify’s unknown next track keeps users in a constant state of monitoring.
- Hidden menus force users to rely on memory rather than habit.

### Design Rule
Interfaces should reduce uncertainty by making outcomes predictable.

### Wireframe Implications
- Clear previews  
- Transparent task flows  
- Stable navigation structures  

---

## Principle 4: Match System Pace to Human Cognition

### Psychological Basis
Humans process information sequentially.  
Rapid content shifts overload encoding processes, while slower pacing improves comprehension and cognitive comfort.

### Interface Problems
- Fast refreshing feeds  
- Simultaneous visual and auditory stimuli  
- Lack of temporal control  

### Application in This Project
- Instagram’s unstable feed forces constant re parsing of content.
- Spotify combines motion, sound, and recommendations simultaneously.

### Design Rule
Interface pace should adapt to **human processing speed**, not maximize engagement.

### Wireframe Implications
- Reduced motion  
- Calm default states  
- Optional stimulation rather than mandatory engagement  
