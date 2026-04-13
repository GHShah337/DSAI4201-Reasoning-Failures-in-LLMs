# Perception and Spatial Reasoning Prompts

This file contains all prompts used to evaluate LLMs and VLMs across perception, spatial reasoning, and prediction-based tasks.

---

## Character Detection

**Prompt:**
Which character is highlighted with a red oval?  
Return your answer in curly brackets (e.g., {a})

---

## Intersection Counting

**Prompt:**
Count the number of line intersections in the image.  
Return only the number.

---

## Nested Shapes

**Prompt:**
Count the total number of nested squares in the image.  
Return only the number.

---

## Grid Counting

**Prompt:**
Count the number of rows and columns in the grid.  
Return in the format: "X rows and Y columns"

---

## Circle Counting

**Prompt:**
Count the number of circles in the image.  
Return only the number.

---

## Overlap Detection

**Prompt:**
Identify the number of overlapping objects in the image.  
Return only the number.

---

## Relative Position (Spatial Reasoning)

**Prompt:**
Which object is to the left of the triangle?  
Return only the object name.

---

## Stability Prediction (Embodied Reasoning)

**Prompt:**
Given the arrangement of objects, determine whether the structure is stable or unstable.  
Return only: Stable or Unstable.

---

## Motion Outcome Prediction

**Prompt:**
Given a sequence of frames showing object movement, predict the final state of the objects.  
Provide a short answer describing the outcome.

---

## Collision Prediction

**Prompt:**
If an object moves forward in the scene, which object will it collide with first?  
Return only the object name.

---

## Embodied Task (Platform Problem)

### Free-text Version
Look at the image.  
The agent needs to reach the platform using the available objects.  
Explain the best strategy step by step.

### One-sentence Version
Look at the image.  
The agent needs to reach the platform using the available objects.  
Give the best action in one sentence.

