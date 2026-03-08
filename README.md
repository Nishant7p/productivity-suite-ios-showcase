# ProductivitySuiteApp – iOS Architecture Showcase

This repository is a **technical showcase** of an iOS productivity and mindfulness application originally developed during an internship.

Due to company confidentiality and non-disclosure policies, the **source code cannot be publicly shared**.  
This repository instead provides an overview of the application's **features, architecture, design decisions, and UI screenshots**.

The goal is to demonstrate the **system design, modular architecture, and engineering approach** used while building the application.
# ProductivitySuiteApp

A modular **iOS productivity and mindfulness application** built using **SwiftUI and MVVM architecture**.
The app combines multiple productivity and mental-wellness tools into a single unified experience to help users stay focused, calm, and consistent throughout their day.

The goal of this project was to design a **clean, extensible productivity ecosystem** rather than a single isolated feature.

---

# Overview

ProductivitySuiteApp integrates multiple micro-tools that support daily productivity and mental clarity.
Instead of switching between different apps for focus timers, meditation, breathing exercises, and quick reflections, users can manage everything from one place.

The project emphasizes:

• Modular architecture
• Clean UI with SwiftUI
• Reusable components
• Clear separation between UI and business logic

---
## App Preview

![App Dashboard](https://i.postimg.cc/XqxcpK69/Screenshot-2025-07-24-at-9-55-43-AM.png)

## Screenshots

| | | |
|---|---|---|
| ![](https://i.postimg.cc/gjM8YY3D/Screenshot-2025-07-24-at-10-00-16-AM.png) | ![](https://i.postimg.cc/zXtFNkjr/Screenshot-2025-07-24-at-10-00-23-AM.png) | ![](https://i.postimg.cc/ZnJxb72T/Screenshot-2025-07-24-at-10-00-52-AM.png) |
| ![](https://i.postimg.cc/rm19LXhn/Screenshot-2025-07-24-at-10-01-49-AM.png) | ![](https://i.postimg.cc/7L73gryH/Screenshot-2025-07-24-at-9-55-52-AM.png) | ![](https://i.postimg.cc/W1d61JWJ/Screenshot-2025-07-24-at-9-56-18-AM.png) |
| ![](https://i.postimg.cc/4dgzP2Jz/Screenshot-2025-07-24-at-9-56-39-AM.png) | ![](https://i.postimg.cc/FRV0BbRw/Screenshot-2025-07-24-at-9-58-35-AM.png) | ![](https://i.postimg.cc/h400ynQh/Screenshot-2025-07-24-at-9-58-50-AM.png) |
# Features

## Focus Tools

### Pomodoro Timer

A customizable Pomodoro timer designed for deep work sessions.

Features:

* Adjustable focus duration
* Custom break intervals
* Alarm sounds
* Session tracking logic

### Deep Work Timer

Designed for longer uninterrupted work sessions.

Features:

* Adjustable duration
* Minimal distraction UI
* Visual countdown interface

---

## Mindfulness Tools

### Meditation Timer

A configurable meditation experience.

Features:

* Custom meditation duration
* Calm UI design
* Start / pause / stop support
* Meditation completion feedback

### Breathing Exercises

Guided breathing exercises to improve focus and reduce stress.

Features:

* Multiple breathing patterns
* Smooth animated breathing cycle
* Exercise selection screen

---

## Wellness Tools

### Power Nap Timer

A quick nap timer designed to recharge energy levels.

Features:

* Adjustable nap durations
* Gentle alarm sounds
* Simple countdown interface

### Sunlight Reminder

Encourages users to take short breaks and get natural sunlight.

Features:

* Quick activity tracking
* Minimal interaction design

---

## Daily Productivity System

### Daily Check-in

Users can reflect on their daily state.

Possible inputs include:

* Mood
* Energy level
* Focus level

### Task Capture

Allows users to quickly record tasks or priorities for the day.

### "Eat The Frog"

Encourages users to complete the most important task first.

---

## Focus Sound Environment

Users can play ambient sounds while working.

Examples include:

* Forest ambience
* Ocean sounds
* Soft background focus audio

These sounds are designed to improve concentration during deep work sessions.

---

# Architecture

The project follows a **Model-View-ViewModel (MVVM)** architecture.

Benefits of this approach:

* Clear separation of concerns
* Better code maintainability
* Easier testing
* Scalable structure

### Architecture Layers

**View**

* SwiftUI UI components
* Screens and reusable UI views

**ViewModel**

* Handles application logic
* Manages state
* Communicates between UI and models

**Model**

* Data structures
* User activity representations
* Domain objects

---

# Project Structure

```
ProductivitySuiteApp
│
├── DailyJourney
│   ├── Cards
│   ├── DailyJourneyView
│   └── ViewModels
│
├── FocusTools
│   ├── Pomodoro
│   ├── DeepWork
│   └── FocusSounds
│
├── MeditationApp
│
├── BreathingApp
│
├── NapTimerApp
│
├── SunlightApp
│
├── SystemDesign
│   ├── UserActivityModels
│   ├── DomainLayer
│   └── RepositoryPattern
│
├── Assets
│
└── Core Components
```

The codebase is organized into **independent feature modules**, making it easy to expand the application with new tools.

---

# Tech Stack

**Language**

Swift

**Frameworks**

SwiftUI

**Architecture**

MVVM

**Tools**

Xcode
Git
GitHub

---

# Design Principles

This project focuses on several core design ideas.

### Modularity

Each feature is implemented as a small independent module.

### Reusable Components

Common UI components such as cards and buttons are reused across multiple screens.

### Clean State Management

ViewModels manage state separately from UI logic.

### Simplicity First

The UI is designed to remain minimal and distraction-free.

---

# Security Notice

Sensitive configuration files such as API credentials and service configuration files have been removed from this repository before publishing.

---

# Future Improvements

Planned improvements include:

* Cloud sync for user activity
* Data analytics for productivity patterns
* Apple Health integration
* Focus session statistics
* Improved animation system

---

# Learning Goals

This project was built to practice:

* Building complex SwiftUI applications
* Implementing MVVM architecture
* Designing modular mobile systems
* Structuring scalable iOS codebases

---

# Author

Nishant Tomer

iOS Developer passionate about building clean and thoughtful productivity tools.

---

# License

This project is intended for educational and portfolio purposes.
