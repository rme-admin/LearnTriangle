# Project Documentation: Learn Triangle

## 1. Project Overview
**Project Name:** Learn Triangle  
**Platform:** Mobile Application (iOS & Android)  
**Framework:** Flutter  
**Core Concept:** A peer-to-peer, free skill-exchange platform that connects knowledge seekers and experts. The app allows users to upskill by learning from others while teaching what they already know, creating a collaborative "triangle" of continuous learning.  
**Primary Revenue Model:** Google Ads Revenue (Phase 1).

## 2. The "Learn Triangle" Concept (Scenario)
The namesake of the app comes from the cyclical, interconnected nature of skill-sharing. 

**Example Scenario:**
*   **User A:** Wants to learn different English accents; is an expert in Programming.
*   **User B:** Wants to learn Programming; is an expert in Data Analysis.
*   **User C:** Wants to learn Data Analysis; is an expert in the American English accent.

**The Triangle Execution:**
User A teaches User B (Programming). User B teaches User C (Data Analysis). User C teaches User A (American English). The platform connects these dots, ensuring everyone gets to upskill without financial barriers.

## 3. User Journey & Registration
### 3.1 Onboarding Data Collection
To ensure platform safety and tailored matching, users will provide the following upon registration:
*   Full Name (Private)
*   Email Address (Private)
*   Phone Number (Private)
*   **Anonymous User Name (Publicly visible to other users)**
*   Gender
*   Location (City/Region - to facilitate potential offline meetups)

### 3.2 Skill Profiling
After basic registration, users must define their learning ecosystem:
*   **Expertise Tag:** What they are experts in / What they can teach.
*   **Desired Skill Tag:** What they want to learn.

## 4. Core Features
### 4.1 Anonymous Matching System
*   Users can search or swipe through a list of people who possess the skills they want to learn.
*   **Total Privacy:** The system masks real identities. Users only see the "Anonymous User Name", the skill the person can teach, the skill the person wants to learn, and general location (e.g., New York, US).

### 4.2 In-App Communication Hub
To facilitate learning without compromising user phone numbers or external social media profiles, the app features:
*   **Text Chatting:** Real-time messaging with file/code-snippet sharing capabilities.
*   **Audio Calling:** In-app audio calls.
*   **Video Calling:** High-quality in-app video conferencing for face-to-face tutoring.

### 4.3 Flexible Learning Modes
*   **Online Learning:** Users can complete their learning journey entirely within the app using the video/audio and chat features.
*   **Offline Meetups:** Because location data is collected, users in the same city can coordinate via the secure app chat to meet at a public place (coffee shop, library) to study in person.

## 5. Monetization Strategy (Phase 1)
As a free platform aimed at democratizing education, the app will generate revenue primarily through **Google Ads**.
*   **Banner Ads:** Displayed at the bottom/top of match lists and chat menus.
*   **Interstitial Ads:** Displayed between major user actions (e.g., after completing a profile, or concluding a video call).

## 6. Technical Stack Details
### 6.1 Frontend (Client-Side)
*   **Framework:** Flutter (Dart). Chosen for a single codebase that deploys natively to both Android and iOS.
*   **Ads Integration:** Google AdMob plugin for Flutter.

### 6.2 Backend & Infrastructure
*   *Note: Backend infrastructure, database architecture, and specific APIs for video/audio communication will be determined and documented in a later development phase.*

## 7. Safety, Privacy & Moderation
Because users operate anonymously and have the option to meet offline, safety is paramount:
1.  **Identity Masking:** Real names, emails, and phone numbers are securely locked and never exposed to the frontend or other users.
2.  **In-App Reporting:** Users can report or block others for inappropriate behavior during chats or video calls.
3.  **Meetup Guidelines:** An automated safety message will be displayed in the chat when users mention meeting up (e.g., "Always meet in public places, do not share financial information").

## 8. Summary of User Flow
1.  **Sign Up:** User enters personal details and creates an anonymous Username.
2.  **Setup:** User selects "Expert In: [Skill]" and "Wants to Learn: [Skill]".
3.  **Discover:** App presents a feed of users whose skills complement the user's needs.
4.  **Connect:** User sends a "Connection Request" to a potential learning partner.
5.  **Communicate:** Once accepted, the chat unlocks.
6.  **Learn:** Users schedule an in-app video call or arrange a local public meetup to share knowledge.

***
*Document Version: 1.1*  
*Created for: Learn Triangle Development & Stakeholder Team*
