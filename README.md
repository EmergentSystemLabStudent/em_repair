# REPAIR

## Description
This repository provides Robot Execution with Planned And Interactive Recovery (REPAIR).

* **Maintainer:** Shoichi Hasegawa (hasegawa.shoichi@em.ci.ritsumei.ac.jp)  
* **Author:** Shoichi Hasegawa (hasegawa.shoichi@em.ci.ritsumei.ac.jp)

---

## Table of Contents
- [Prompts Folder Structure](#prompts-folder-structure)
- [References](#references)

---

## Prompts Folder Structure
The `prompts` folder contains the following prompt files. Use them as needed:

### REPAIR
- **Task_decomposition_allocation_prompts.txt**  
  Prompt for task decomposition and allocation by an LLM.
- **semi_autonomous_planning_prompt.txt**  
  Prompt for action planning with help skills by an LLM.

### State_Recognizer
- **state_recognizer_prompt_about_grasping.txt**  
  Prompt for state recognition from an RGB image that captures grasping by a VLM.
- **state_recognizer_prompt_about_placing.txt**  
  Prompt for state recognition from an RGB image that captures placement by a VLM.

#### Auto
- **autonomous_planning_prompt.txt**  
  Prompt for action planning by an LLM.

---
