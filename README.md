# food-rescue-system
Web-based Food Rescue Management System for campus

# Food Rescue Management System

## 1.1 Introduction
The proposed application is a web-based Food Rescue Management System developed using the Laravel Framework. The purpose of this system is to connect event organizers on campus such as student societies, Mahallah administrations, and departmental units with students who need meals. Many campus events involve catering, often resulting in surplus food. This system enables organizers to post real-time alerts whenever excess food is available so that students can quickly collect it.

The main goal is to minimize food wastage while providing a convenient, Shariah-compliant method for food redistribution within the university.

## 1.2 Problem Description

### 1.2.1 Background of the Problem
Currently, the university hosts numerous events, seminars, and meetings daily, often involving catering. Frequently, there is a surplus of food left over after these events. At the same time, many students are looking for affordable meal options. The current environment lacks a centralized digital platform to bridge this gap; organizers often resort to scattered WhatsApp messages or simply throw the food away.

### 1.2.2 Problem Statement
- **Wastage (Israf):** Significant amounts of good food are discarded because there is no quick way to inform the student body of its availability before it spoils.  
- **Inefficient Communication:** Information about free food is shared via limited WhatsApp groups, meaning many students who need it miss out.  
- **Lack of Tracking:** Organizers have no way to verify if the food was collected or manage the crowd, leading to potential disorder or "first-come-first-serve" chaos.

## 1.3 Project Objective
The objectives of this project are:

- To develop a real-time web platform that enables organizers to post leftover food alerts efficiently.  
- To allow students to view and claim available food based on location, time, and food quantity.  
- To reduce food wastage on campus by improving distribution speed and communication.  
- To implement CRUD-based automation, including creating, updating, and removing food alerts, reducing reliance on manual announcements.  
- To generate basic data records on the number of posts, claims, and completed distributions, which can be used for sustainability reporting.

## 1.4 Features & Functionalities
**User Authentication:**  
- Supports login and registration for organizers and students, ensuring secure access.  
- Role-based access control to provide appropriate permissions for each user type.

**Organizer Functions:**  
- Create detailed food alerts with photo, location, quantity, and pickup time to inform students clearly.  
- Update food status (Available → Low → Finished) to reflect real-time availability.  
- Edit or delete postings when information changes.  
- Access a simple statistics dashboard (optional) for monitoring distributions.

**Student Functions:**  
- View all real-time food alerts posted by organizers.  
- Filter alerts by location, time, or food availability for easier searching.  
- Reserve food items if the feature is enabled.  
- Mark items as collected to complete the distribution process.

**Admin Functions:**  
- Manage and monitor all user accounts within the system.  
- Approve, edit, or remove alerts that violate rules.  
- Generate basic usage reports for oversight and sustainability tracking.

**System Features:**  
- Built with Laravel using full MVC architecture for structured development.  
- Provides complete CRUD operations for food posts and user management.  
- Mobile-responsive interface for convenient access on any device.

## 1.5 Constraints
The effectiveness of this system relies heavily on user responsiveness, as organizers must post food alerts promptly for real-time distribution to work as intended. Since the platform operates fully online, users also need a stable internet connection to access updates, view available food alerts, and interact with the system. Additionally, the overall success of the platform depends on strong community adoption and engagement; without active participation from both organizers and students, its impact on reducing food wastage will be limited.

## 1.6 Project Stages
The development of this project is divided into three structured phases to ensure smooth progress and clear deliverables. Phase 1 focuses on preparing and submitting the project proposal by 11 December 2025, outlining the system concept, objectives, and initial design. Phase 2 represents the core development period, during which the database structure, routing setup, and controller functions will be designed and implemented between December and January 2026. Finally, Phase 3 involves completing the full system and preparing for the final submission, which includes a presentation and a live demonstration on 7 January 2026 to showcase the project’s functionality and overall performance.

## 1.7 Significance of the Project
This project carries several important benefits for the university community. For the university, it supports ongoing sustainability initiatives by helping reduce the amount of food waste generated on campus, which in turn can lower waste management and disposal costs. For students, the platform provides easy access to leftover meals shared by organizers, allowing them to better manage their daily food expenses and helping lessen their financial burden, especially for those facing economic constraints. From an Islamic perspective, the project aligns strongly with values that prohibit wastage (israf) and encourage acts of kindness such as sadaqah and community support, making the system not only practical but also ethically meaningful.
