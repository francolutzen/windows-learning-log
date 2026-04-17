# Browser Privacy Basics Lab

## Objectives

* Analyze basic web privacy risks in a common browsing environment.
* Identify third-party cookies and external scripts loaded by everyday websites.
* Compare default browser behavior versus privacy-enhanced settings.
* Evaluate how simple tools can reduce trackable data exposure.
* Build practical familiarity with browser developer tools and privacy controls.

## Test Environment

* Oracle VM VirtualBox
* Windows 10 22H2
* 4 GB RAM
* 2 Virtual CPU Cores
* Simulated average user scenario

## Phase 1 — Baseline Browser Behavior (Default Configuration)

### Purpose

Establish a reference point using a standard browser installation with default settings before applying any privacy protections.

### Actions Performed

* Installed a web browser with default configuration.
* Visited common everyday websites (news, shopping, video, search, social platforms).
* Opened Developer Tools to inspect:

  * Cookies
  * Network requests
  * Third-party domains
  * Loaded scripts
* Observed visible ads, consent banners, pop-ups, and trackers.
* Recorded initial behavior without extensions or custom blocking rules.

### Data Collected

* Number of third-party requests
* Presence of tracking / analytics domains
* Cookies created during session
* Page load behavior
* User experience under default settings

### Expected Outcome

Measure how much external activity occurs in a normal browsing session when the average user makes no privacy changes.

# Test Environment Ready

<img width="1919" height="1157" alt="01-test-environment png" src="https://github.com/user-attachments/assets/9100bc28-a59b-4c08-923e-3b77464af809" />
Initial controlled environment used to simulate an average Windows user browsing session.

# Clean Browser Default State

<img width="1919" height="1150" alt="02-browser-default-state png" src="https://github.com/user-attachments/assets/bd14cfd3-7b8e-46fa-8a3d-63d3e6bacf96" />
Fresh installation of Google Chrome running with default settings, no extensions installed, and no custom privacy protections enabled.

# Simulated Active Browsing Session

<img width="1919" height="1152" alt="03-simulated-active-session png" src="https://github.com/user-attachments/assets/67346390-f7bc-4cf8-8ce9-9b21cb8a5a2e" />
Simulated average user browsing session with multiple open tabs including e-commerce, news, travel, and video platforms under default browser settings.

# Network Tab Capture

<img width="1919" height="1124" alt="04-network-tab-capture png" src="https://github.com/user-attachments/assets/878267c9-064d-496d-bafe-5ae168f108ca" />
Chrome Developer Tools showing the Network tab with basic HTTP requests loaded after refreshing a webpage. The view displays different resource types such as images, scripts, and stylesheets.




