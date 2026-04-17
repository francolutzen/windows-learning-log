# Windows Startup Impact Analysis

## Objectives

- Demonstrate how a standard Windows system with defaults settings and commonly used applications can experience performance slowdowns due to excessive startup programs and unnecesary background processes

- Analyze the impact of startup applications on system performance and compare basic optimizations strategies

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

### Note

Not all installed applications appear in the Startup tab. Only programs configured to launch atomatically at system startup are listed. Other applications may still run manually or generate background processes during use.

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

### Expected Effects
* Lower idle RAM usage
* Reduced number of background processes
* Improved system responsiveness during startup

# Task Manager - Startup (After Optimization)

<img width="1919" height="1150" alt="After Optimization - Startup" src="https://github.com/user-attachments/assets/075349d4-da3b-4a00-96d7-4d1e3c25bcd8" />

Most startup applications have been disabled, leaving only essentials processes such as Microsoft Edge and OneDrive enabled.

# Task Manager - Processes (After Optimization)

<img width="1919" height="1151" alt="After Optimization - Processes" src="https://github.com/user-attachments/assets/1f1826f4-f4e0-4591-8dfd-77e4c249ffe7" />

The number of active background processes has been reduced after disabling non-essentials startup applications.
This is reflected in a clear reduction in resource usage, with CPU usage decreasing from around 50-70% to roughly 5%-20%

# Task Manager - Performance (CPU) (After Optimization)

<img width="1919" height="1125" alt="After Optimization - CPU Performance" src="https://github.com/user-attachments/assets/a628a058-02e6-41bd-adfb-9f52d4b478d5" />

CPU Usage remains low under normal conditions, typically ranging between 3-10%, with occasional short spikes that can reach higher values (around 30-40%) due to background system activity.

# Task Manager - Performance (Memory) (After Optimization)

<img width="1919" height="1154" alt="After Optimization - RAM" src="https://github.com/user-attachments/assets/1de6ad90-1805-4333-9362-aa40635fea55" />

Memory usage remains stable after optimization, maintaining a consistent level around 50% with only minor fluctuations. 
This indicates reduced background activity and more efficient resources usage compared to the previous state.

### Summary

Disabling non-essential startup applications significantly reduced background activity, resulting in lower CPU and memory usage, as well as improved system stability.

## Conclusion

This basic project demonstrates how simple startup configuration changes in Windows 10/11 can reduce background resource usage and improve system responsiveness during idle conditions.
The results show a clear difference between an overloaded startup environment and a minimal optimized configuration





















