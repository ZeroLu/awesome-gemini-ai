# Awesome Gemini AI ♊️

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![Gemini](https://img.shields.io/badge/Google%20DeepMind-Gemini-blue?style=flat-square)](https://deepmind.google/technologies/gemini/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

> A curated collection of the **best Gemini prompts**, use cases, and resources for Google's Gemini 3 Pro, Flash, and Ultra models.

This repository focuses on **high-performance prompts** sourced from X (Twitter), Reddit, and top prompt engineers. Whether you are looking for **Gemini coding prompts**, **UI/UX design generation**, or creative experiments, you will find the most effective inputs here to unlock the full potential of the 1M+ token context window.

## 📖 Table of Contents

1. [Web Development & Coding](#1-web-development--coding)
2. [UI/UX & Design](#2-uiux--design)
3. [Creative & 3D Experiments](#3-creative--3d-experiments)
4. [Multilingual Prompts (Chinese/CN)](#4-multilingual-prompts-chinesecn)
5. [Resources](#5-resources)
6. [Contributing](#6-contributing)

---

## 1. Web Development & Coding

Optimize your workflow with these **Gemini coding prompts**. These are designed to utilize Gemini's reasoning capabilities to build complex applications in a single shot.

### 1.1. Futuristic AI Agency Landing Page (Next.js 14)
*A massive context prompt to generate a high-performance, award-winning style website.*
<img width="500" alt="image" src="https://github.com/user-attachments/assets/c79621eb-a40a-4f3d-8217-12696c7c52dd" />

**Prompt:**
```text
You are an award-winning Creative Developer and UI/UX Designer known for building Awwwards-winning websites. You specialize in "AI-First" aesthetics using shaders, glassmorphism, and fluid motion to create interfaces that feel alive.

Task:
Build a high-performance, interactive landing page for an AI Software Development Agency using Next.js 14 (App Router), Tailwind CSS, Framer Motion, and React Three Fiber (for shaders).

Agency Services (Content):
The agency helps clients build:
- AI Full-Stack SaaS (Next-gen applications)
- AI Agents (Autonomous worker bots)
- RAG Pipelines (Retrieval-Augmented Generation)
- Custom Video Solutions (AI video generation/editing tools)
- Custom n8n Workflows (Advanced automation)

Design "Skill" & Guidelines (STRICT ADHERENCE REQUIRED):
Refusing generic "AI Slop" design patterns is your highest priority.

Typography (Crucial):
- DO NOT USE: Inter, Roboto, Open Sans, Segoe UI, or system defaults.
- USE: distinctive, technical fonts.
- Headings: Space Grotesk or Syne (Bold, tight tracking).
- Body: JetBrains Mono or DM Sans (Clean, legible, technical feel).
- Rule: Use extreme contrast in weights (Light 200 vs Black 800) and large size jumps.

Visuals & Atmosphere:
- Backgrounds: Never use solid flat colors. Create "Atmosphere." Use deep, dark voids (#030305) layered with radial gradients, mesh gradients, or subtle noise textures.
- Shaders: Implement a background shader (using React Three Fiber or a GLSL canvas) that reacts to mouse movement.
- Color Palette: Dark Mode focus. Deep Obsidian / Midnight Blue backgrounds with sharp, neon accents (Electric Blue #3B82F6, Cyber Purple #8B5CF6, or Acid Green).

Motion & Interactivity:
- Staggered Reveals: Do not fade everything in at once. Use framer-motion to stagger children elements.
- Scroll Animations: Elements should float up, blur-in, or scale up as the user scrolls.
- Micro-interactions: Buttons should have magnetic effects or liquid hover states. Cards should tilt (3D parallax) on hover.

Layout:
- Avoid standard Bootstrap/Centered layouts.
- Use Bento Grids (asymmetrical grid layouts) for the Services section.
- Use overlapping elements and negative space to create depth.

Implementation Plan:
- Header: A holographic glassmorphism navbar.
- Hero Section: massive typography, shader background, "Book a Call" button with a glowing border.
- Services (The Bento Grid): A responsive grid showcasing the 5 services mentioned above.
- Why Us: A section explaining the "AI First" approach using a comparison UI (Old Way vs. AI Way).
- Footer: massive interactive footer with a "let's build the future" marquee.

Output:
Write the complete, functional code for the landing page (in React.js). If you need to split components, provide them in a logical order. Start by defining the shader component, then the UI components, then the main page assembly.
```
*Source: [@code_bucks](https://x.com/code_bucks/status/1990880415104544984)*

### 1.2. Enterprise Landing Page Generator
*Great for quickly mocking up professional business pages.*

<img width="500" alt="image" src="https://github.com/user-attachments/assets/c3ee3234-68bc-41f6-b42e-f20280044571" />

**Prompt:**
```text
Generate an enterprise-grade professional [DESCRIBE YOUR BUSINESS] landing page. 

Add interactive elements, animations, and make it fully responsive. 

Surprise me, be creative, do this step by step.
```
*Source: [@godofprompt](https://x.com/godofprompt/status/1991146150859039013)*

### 1.3. "Winnux" OS Simulator
*A complex prompt testing Gemini's ability to manage state and simulate operating systems.*
<img width="500" alt="image" src="https://github.com/user-attachments/assets/b2331d06-ef6f-46c1-9ac2-cdb6f843a626" />

**Prompt:**
```text
Build a fully functional web application fully simulating an OS. Make a blend of Windows 11 and Linux, call it Winnux. The UI must completely copy the windows 11 vibe and has apps like in linux.
```
*Source: [@wildmindai](https://x.com/wildmindai/status/1991263000049615096)*

---

## 2. UI/UX & Design

Prompts focused on creating aesthetically pleasing interfaces, shaders, and CSS masterpieces.

### 2.1. Futuristic Crypto Dashboard
<img width="500" alt="image" src="https://github.com/user-attachments/assets/aa928aa5-ff60-4383-b307-41c11a80325c" />

**Prompt:**
```text
Reproduce a futuristic dark-mode crypto dashboard featuring high-contrast obsidian backgrounds, gradient-border glassmorphism UI elements, thin Inter typography, and neon-accented financial data visualizations.
```
*Source: [@RayaneRachid_](https://x.com/RayaneRachid_/status/1990871798095737152)*

### 2.2. Maximalist Design (Digital Hot Dogs)
*Test Gemini's ability to create "trendy" and chaotic design styles (Dithering/Groovy).*
<img width="500" alt="image" src="https://github.com/user-attachments/assets/c95e989b-025a-4448-9fa8-d78030bccba0" />

**Prompt:**
```text
Design a maximalist website for a fictional start up that sells digital hot dogs. I want beautifully animated hero text with shaders that interact with mouse hover. lots of dithering, wavy, groovy, gradients.
```
*Source: [@benhylak](https://x.com/benhylak/status/1991225744194691289)*

### 2.3. Jarvis HUD Interface
<img width="500" alt="image" src="https://github.com/user-attachments/assets/7ee68e9c-554b-4783-86e4-bb4c2300619a" />

**Prompt:**
```text
Build a jarvis HUD interface for tony stark.
```
*Source: [@measure_plan](https://x.com/measure_plan/status/1991166530952810514)*

---

## 3. Creative & 3D Experiments

Using libraries like Three.js, React Three Fiber, and MediaPipe via Gemini.

### 3.1. 3D Interactive Radio Globe
<img width="500" alt="image" src="https://github.com/user-attachments/assets/4dbb6414-f795-43f2-abcd-7ce9e968272b" />

**Prompt:**
```text
A fully interactive 3d globe that lets you explore and stream radio stations from around the world.
```
*Source: [@sahilypatel](https://x.com/sahilypatel/status/1991192711139930187)*

### 3.2. Laser Eye Effect (CV + Three.js)
<img width="500" alt="image" src="https://github.com/user-attachments/assets/100a1ef5-f2e1-42dc-bbf3-88044f46e09e" />

**Prompt:**
```text
- Use the computer's front-facing camera
- Use `mediapipe` lib to capture facial landmarks
- Use `threejs` to apply a LASER EYE effect to the face captured by the camera based on the real-time 3D landmark information provided by `mediapipe`
```
*Source: [@fangyex](https://x.com/fangyex/status/1991186281704173931)*

---

## 4. Multilingual Prompts (Chinese/CN)

Gemini is excellent at handling multilingual coding requests.

### 4.1. Web-Based Rich Text Editor (Word Clone)
<img width="500" alt="image" src="https://github.com/user-attachments/assets/9a8e11b1-8ac8-4fbb-b3e8-0ec7a3950e0b" />

**Prompt:**
```text
帮我写一个类似word的网页版富文本编辑器，包含它的主要功能，所有代码放在一个html文件里。
```
*(English Translation: Help me write a Word-like web-based rich text editor, including its main functions, put all code in one html file.)*
*Source: [@karminski3](https://x.com/karminski3/status/1991136616312963096)*

### 4.2. KOL Ranking List Landing Page
<img width="500" alt="image" src="https://github.com/user-attachments/assets/16bb4a0d-bbd8-4a99-96f3-50f1921b74ff" />

**Prompt:**
```text
作为一名极具审美的前端工程师，创建一个「中文推特 KOL 榜单」网站落地页，设计感拉满，极简配色，深色模式，高对比度。数据源通过网络获取。
使用 tailwindcss + html5 ，加入动效，直接输出 HTML 代码。
```
*(English Translation: As a frontend engineer with great aesthetics, create a "Chinese Twitter KOL List" website landing page, full design sense, minimalist color scheme, dark mode, high contrast. Fetch data sources via network. Use tailwindcss + html5, add animation, output HTML code directly.)*
*Source: [@hellokaton](https://x.com/hellokaton/status/1991044658638840304)*

---

## 5. Resources

- [Google AI Studio](https://aistudio.google.com/) - The best place to test these prompts with Gemini 3 Pro / Flash.
- [DeepMind Gemini Docs](https://deepmind.google/technologies/gemini/) - Official documentation.

## 6. Contributing

Contributions are welcome! If you have an **awesome Gemini prompt**, please submit a Pull Request.

1. Fork the repo.
2. Create a new branch.
3. Add your prompt in the correct category with the next available number (e.g., `1.4`, `2.4`).
4. Submit PR.

Please ensure you include the **Source** (link to the original creator) to give credit where it is due.
