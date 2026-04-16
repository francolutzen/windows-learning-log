# Startup Optimization Based on User Needs

## Objectives

- Demonstrate how a standard Windows system with defaults settings and commonly used applications can experience performance slowdowns due to excessive startup programs and unnecesary background processes

- Analyze the impact of startup applications on system performance and compare basic optimizations strategies tailored to different user needs.

## Test Environment

* VirtualBox
* Windows 10 Version 22H2
* 4 GB RAM
* 2 virtual CPU cores
* Simulated average user scenario

## Installed Applications

* Spotify
* Discord
* Steam
* Microsoft Teams
* Microsoft 365 Copilot
* Notion
* CapCut
* Canva
* Adobe Acrobat Reader
* VLC Media Player
* Zoom Workplace
* Candy Crush Saga

---

## Phase 1 - Saturated Startup Environment

All common applications enabled at startup to simulate an overloaded everyday system.

### Expected Effects

* Higher idle RAM usage
* More background processes
* Slower startup responsiveness

# Test Environment Overview

<img width="1919" height="1118" alt="test-environment-overview" src="https://github.com/user-attachments/assets/182526fe-dad4-4d2b-b585-a9478caf2339" />

This image shows the test environment with commonly used applications installed to simulate a typical user setup.

# Task Manager - Processes (Before Optimization)

<img width="1919" height="1152" alt="Before Optimization - Task Manager" src="https://github.com/user-attachments/assets/4e6f3390-7c39-4581-8043-e0fbae8baa2e" />

The system shows multiple active background processes, increasing CPU and memory usage even in idle state

# Task Manager - Performance (CPU) (Before Optimization)

<img width="1919" height="1121" alt="Before Optimization - CPU Performance" src="https://github.com/user-attachments/assets/b9b89085-91a4-4382-8bc1-5c6d946cf654" />

The CPU usage is consistenly high even without active user interaction. This indicates that multiple background processes are consuming system resources.

# Task Manager - Performance (Memory) (Before Optimization)

<img width="1919" height="1122" alt="Before Optimization - RAM" src="https://github.com/user-attachments/assets/351b6f11-fbbd-4733-911a-abd5e68c4f9a" />

Memory usage remains relatively high due to multiple background applications running simultaneously. This limits the amount of avaliable RAM for other tasks and can impact overall system responsiveness.

# Task Manager - Startup (Before Optimization)

<img width="1919" height="1151" alt="Before Optimization - Startup" src="https://github.com/user-attachments/assets/bd1f2a52-4821-42db-9ff4-7b1e05095405" />

Task Manager Startup tab showing multiple applications enabled to launch automatically with Windows.

## Phase 2 - General Startup Optimization

- This phase focuses on reducing unnecesary background activity by disabling non-essential startup applications. The goal is to create a cleaner system without prioritizing any specific user profile.

### Task Manager - Startup (After Optimization)

<img width="1919" height="1150" alt="After Optimization - Startup" src="https://github.com/user-attachments/assets/075349d4-da3b-4a00-96d7-4d1e3c25bcd8" />

Most startup applications have been disabled, leaving only essentials processes such as Microsoft Edge and OneDrive enabled.





