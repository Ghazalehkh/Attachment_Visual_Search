# Attachment Visual Search Task

A computerized neuropsychological experiment designed to assess visual attention, attentional bias, and reaction times in response to attachment-related emotional stimuli.

---
## 📌 Project Overview
This task is a specialized Visual Search Task utilizing a $3 \times 3$ stimulus matrix. The underlying psychological framework relies on Attachment Theory. The stimuli consist of distinct attachment-related images (e.g., secure, anxious, avoidant, or neutral attachment representations) to measure how internal working models of attachment influence visual search efficiency, selective attention, and cognitive processing speeds.
---

## 🎮 Task Design & Layout

1. **Instruction Screen:** The participant is presented with the task instructions in Persian. They start the experiment by pressing the **Spacebar**.
2. **Trial Configuration:**
   * **Target Image:** Displayed in isolation on the **left side** of the screen.
   * **Search Array:** A $3 \times 3$ grid containing 9 images displayed on the **right side** of the screen. One of these images matches the target exactly; the other 8 act as distractors.
3. **Participant Objective:** Find the matching target inside the matrix as quickly and accurately as possible and click on it using the mouse.

## 📊 Recorded Metrics & Output Data

The task automatically records behavior on a trial-by-trial basis and exports the data into a structured format (e.g., `.csv` files) inside the output directory[cite: 1]. The primary dependent variables are:

* `Reaction_Time` (RT): The precise time in milliseconds from the onset of the matrix display until the participant registers a mouse click.
* `Clicked_Image`: The identity/filename of the image the participant selected (used to evaluate accuracy, missed targets, or specific distractor interference)
* `Target_Image`: The identity of the correct item
* `Is_Correct`: A boolean value (1 or 0) representing whether the correct target was clicked

---

## 📁 Repository Structure

```text
├── Visual Search/
│   ├── stimuli/         # Attachment-related images grouped by emotional valence/type
│   └── trials/          # instruction blocks and trials' design
│   └── code/            # 
└── README.md            # Project documentation
```

## 🧠 Key Research Applications
* **Attentional Bias:** Analyzing whether individuals with anxious or avoidant attachment styles display hypervigilance (faster RT) or avoidance (slower RT) toward specific attachment cues.
* **Cognitive Psychology:** Studying the impact of emotionally charged, socially relevant distractors on basic visual search performance[cite: 1].
