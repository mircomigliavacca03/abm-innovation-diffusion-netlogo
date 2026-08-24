# Agent-Based Modeling & Innovation Diffusion: Apple vs Samsung Case Study

[![Platform](https://img.shields.io/badge/Simulation-NetLogo-green.svg)]()
[![Course](https://img.shields.io/badge/Course-Seminar%20in%20Topics%20of%20Innovation%20I-blue.svg)]()
[![Academic Year](https://img.shields.io/badge/Academic%20Year-2025-orange.svg)]()

---

## 📌 Project Overview
Research paper and computational simulation developed for the *Seminar in Topics of Innovation I* course (M.Sc. level), under the supervision of **Lecturer Mathias Muller**.

* **Authors:** 
  * Mirco Migliavacca
  * Bianca Elena Costantin
  * Marta Molinari
* **Academic Year:** 2025

---

## 🎯 Research Objectives
This project investigates the dynamics of **innovation diffusion** driven by social interactions, localized word-of-mouth (WOM), and consumer heterogeneity using an **Agent-Based Modeling (ABM)** approach. 

Taking inspiration from the competitive duopoly between **Apple** and **Samsung**, the model simulates how micro-level consumer behaviors aggregate into macro-level market share trajectories.

---

## 🔬 Theoretical Framework & Methodology
* **Rogers' Diffusion of Innovations (1983/2003):** Micro-validation of the emergent S-shaped adoption curve (Innovators, Early Adopters, Majority, Laggards).
* **Generative Social Science (Epstein, 1999):** Growing market patterns bottom-up through autonomous, bounded-rational agents interacting in a Moore neighborhood.
* **Complex Word-of-Mouth (WOM) Networks:** Modeling direct peer influence, tipping points, and the dampening effect of indifferent/resistant consumers (acting as network firewalls).
* **Path Dependence:** Quantifying how minor initial advantages in early adopter populations can lead to complete market lock-in.

---

## 💻 Simulation Implementation (NetLogo)
The model simulates a population of agents with dynamic state transitions:
* **Potential Adopters:** Uninformed agents available for persuasion.
* **Early Adopters / Adopters:** Brand-specific carriers (Apple vs Samsung) transferring adoption probabilities upon contact.
* **Indifferent / Non-Adopters:** Agents resistant to influence, representing real-world market friction.

---

## 📂 Repository Contents
* `SEMINAR IN TOPICS OF INNOVATION I.pdf`: Full academic paper including theoretical background, parameter experiments, and discussion.
* `Appendix / Model Code`: NetLogo simulation script and procedures.
