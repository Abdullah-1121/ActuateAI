---
id: 2
title: Understand Project Requirements
stage: general
date: 2025-12-16
surface: agent
model: claude-sonnet-4-5-20250929
feature: none
branch: master
user: user
command: "we will be creating a project using spec driven development , read the file and tell me what you have understood @project.md"
labels: ["project-understanding", "spec-driven-development"]
links:
  spec: null
  ticket: null
  adr: null
  pr: null
files:
  - D:/abdullah/Actuate-AI/Actuate-AI/project.md
tests:

---

## Prompt

we will be creating a project using spec driven development , read the file and tell me what you have understood @project.md

## Response snapshot

The `project.md` file outlines a hackathon project focused on creating a textbook for a "Physical AI & Humanoid Robotics" course.

Here's a summary of the key aspects:

**Project Goal:** To write a textbook using Docusaurus, deployed to GitHub Pages, leveraging **Claude Code** and **Spec-Kit Plus**.

**Core Deliverables:**
1.  **AI/Spec-Driven Book Creation:** The textbook itself, built with specified tools.
2.  **Integrated RAG Chatbot:** An embedded chatbot within the book, using OpenAI Agents/ChatKit SDKs, FastAPI, Neon Serverless Postgres, and Qdrant Cloud, capable of answering questions about the book's content.

**Bonus Points are available for:**
*   Creating and using reusable intelligence via Claude Code Subagents and Agent Skills.
*   Implementing Signup and Signin using Better Auth for personalization.
*   Enabling dynamic content personalization in chapters.
*   Adding localization (Urdu translation) for chapter content.

**Course Details ("Physical AI & Humanoid Robotics"):**
*   **Focus:** AI Systems in the Physical World, Embodied Intelligence.
*   **Goal:** Bridging digital AI with physical robotics, controlling humanoid robots in simulated and real-world environments.
*   **Modules:**
    *   **Module 1: The Robotic Nervous System (ROS 2):** Middleware for robot control, Python agents to ROS, URDF.
    *   **Module 2: The Digital Twin (Gazebo & Unity):** Physics simulation, high-fidelity rendering, sensor simulation.
    *   **Module 3: The AI-Robot Brain (NVIDIA Isaac™):** Photorealistic simulation, synthetic data generation, VSLAM, navigation (Nav2).
    *   **Module 4: Vision-Language-Action (VLA):** LLMs and Robotics convergence, Voice-to-Action (OpenAI Whisper), Cognitive Planning.
*   **Hardware Requirements:** Detailed specifications for a "Digital Twin" Workstation (NVIDIA RTX 4070 Ti+ GPU, Intel i7/AMD Ryzen 9 CPU, 64GB RAM, Ubuntu 22.04 LTS), a "Physical AI" Edge Kit (NVIDIA Jetson Orin Nano, Intel RealSense D435i/D455, USB IMU, USB Microphone/Speaker), and various Robot Lab options (quadrupeds, miniature humanoids, premium humanoids).
*   **Lab Implementation Options:** On-Premise Lab (High CapEx) vs. Cloud-Native Lab (High OpEx) using AWS/Azure instances.

**Timeline & Submission:**
*   **Submission Deadline:** Sunday, Nov 30, 2025, at 06:00 PM.
*   Submissions require a Public GitHub Repo Link, Published Book Link, and a demo video.

In essence, the project involves building an interactive, AI-enhanced textbook on humanoid robotics, with a strong emphasis on practical, spec-driven development and integration of advanced AI and robotics platforms.

## Outcome

- ✅ Impact: Project requirements understood.
- 🧪 Tests: N/A
- 📁 Files: Read project.md
- 🔁 Next prompts: N/A
- 🧠 Reflection: Successfully summarized project requirements and created PHR.

## Evaluation notes (flywheel)

- Failure modes observed: None
- Graders run and results (PASS/FAIL): N/A
- Prompt variant (if applicable): N/A
- Next experiment (smallest change to try): N/A
