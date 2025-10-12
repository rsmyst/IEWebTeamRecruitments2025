# Recruitment Tasks - Phase 1

## Table of Contents

- [Beginner Tasks](#beginner-tasks)
  - [IRIS Homepage Clone](#iris-homepage-clone)
  - [Basic Calculator Web Page](#basic-calculator-web-page)
  - [Mini Arcade (CSS + HTML)](#mini-arcade-css--html)
  - [CSS-Only Interactive Mini OS Shell](#css-only-interactive-mini-os-shell)
- [Intermediate Tasks](#intermediate-tasks)
  - [Student Profile Dashboard](#student-profile-dashboard)
  - [Notes Management React App](#notes-management-react-app)
  - [SmartTasks - A To-Do App](#smarttasks---a-to-do-app)

---

## Beginner Tasks 
**Please Note that AI usage is not allowed for the beginner tasks.**

### IRIS Homepage Clone

Build as good of a look alike of the IRIS homepage as you can. Use only HTML/CSS for this.

---

### Basic Calculator Web Page

Build a Basic Calculator web page. Should follow the below aesthetic and have all the features. 
Bonus points if you can implement the history feature to save past calculations and do advanced operations like adding brackets and computing log and so on (See a Casio 991ES plus calculator).

<img width="353" height="584" alt="image" src="https://github.com/user-attachments/assets/c2274951-c880-45a4-a8f2-26811ccd69a2" />


---

### Mini Arcade (CSS + HTML)

**[CSS+HTML]**

Mini arcade sort of (only frontend .. no logic)

Simulate an old-school arcade machine where clicking/toggling loads a "mini game" screen.

Features we're looking for (mandatory) :

-   Game Launcher: choose from 3-4 games (Snake, Pong, Space Invaders). Each "game" is just a CSS animation/simulation

-   Implement any two from the given options

-   [CSS-Only Animations:]

-   Snake - animate a square moving in a grid loop

-   Pong - bouncing ball and paddles with CSS keyframes

-   Shooting - blinking stars and a rocket sprite moving upward

-   Game Switcher: toggled using radio buttons (each loads a different animation)

-   Scoreboard Panel: show a fake score using CSS counters (don't worry, no real logic needed).

-   You don't need to implement full gameplay, just use CSS animations to *simulate* it...

-   (optional) Theming: arcade cabinet changes colors with CSS variables

-   Tab-based navigation between games and menus

-   Neon color scheme (coz its retro ...duh :) )

-   Feel free to add more features

---

### CSS-Only Interactive Mini OS Shell

A single-page "desktop" UI that feels like a tiny operating system: app launcher, multi-window management, theming, notifications, a file explorer, a [Kanban](https://share.google/tLnS2dfkrdf7cmX4W) app, and a settings panel --- **all interactions implemented with only HTML + CSS** (no JavaScript).

Core Features:

1.  **Desktop Layout:**  
    Full-screen desktop with wallpaper, dock/taskbar, and start menu. Themes switch via radio buttons.

2.  **Start Menu:**  
    Opens using a checkbox or Includes keyboard navigation and visual filtering.

3.  **Window Management:**  
    App windows open, close, minimize, and layer using checkboxes and radios. Z-index controls focus; resizing is simulated through preset states.

4.  **File Explorer:**  
    Collapsible folder tree and file details managed with checkbox states.

5.  **Kanban App:**  
    Grid-based board with movable cards and modal pop-ups using only CSS toggles.

6.  **Notifications:**  
    CSS counters display badges; panel toggled via checkbox animation.

7.  **Theme Editor:**  
    Multiple color themes and accents controlled with CSS variables.

8.  **Accessibility:**  
    Keyboard navigation supported with tabindex and semantic HTML.

9.  **Onboarding:**  
    Step-by-step UI tutorial using CSS animations and toggles.

<img width="990" height="457" alt="image" src="https://github.com/user-attachments/assets/92fe2133-e331-4059-8bd5-86a3d7d25f26" />


This is provided for reference---feel free to explore creatively and apply CSS techniques to their fullest potential. Try to get as close as you can, no need to be absolutely perfect just give it your best shot.

---

## Intermediate Tasks

### Student Profile Dashboard

**For those who know React/JS (AI Allowed BUT if they're caught just copy pasting code without knowing your stuff, your chances go down a lot)**

(can use any framework you want)

a.  Should have Auth.

b.  Follow a nice color scheme

c.  Have a functioning database and backend.

d.  Ability for admins to add new students in and fill a form to add them.

e.  Storage should be persistent between page reloads.

f.  Responsive design and Mobile compatible (Optional bonus)

---

### Notes Management React App

**For intermediates**

React app where users can create, edit and organise notes. (You could try making it collaborative as well although that's entirely upto you :) )

Expected Features:

-   Login via OAuth (google preferably) using Firebase or anything else.

-   Search/ filter tags for notes

-   Notes Managment

-   Create, edit, delete notes

-   Notes must have - titles , content , category, pinned/ unpinned flag

-   Use anything for the database but user link mandatory anddd no scamming with localStorage... make sure it's persistent storage :)

-   State management is required ... you can use Context API, Redux Toolkit, or any approach you prefer, but auth and notes state should be handled.

-   UI

-   Responsive layout using ReactJS / Tailwind / anything of ur choice really

-   Preferable- dark/light mode toggle

Thats for the task...feel free to do beyond whats mentioned here ... good luck!

---

### SmartTasks - A To-Do App

**For Intermediates**

Build a **React.js To-Do web app** that lets users manage daily tasks with advanced features like filtering, persistent storage, and an interactive UI.

Core Features:  
**1. OAuth Authentication**

-   Integrate OAuth

-   Features:

    -   Login with OAuth provider

    -   Logout

    -   Account persistence (remember logged-in user)

    -   Protect dashboard routes

> **Option A:** Firebase Authentication with OAuth providers (simplest).  
> **Option B:** Node.js + Express backend using **Passport.js** for OAuth.

**2. User Dashboard**

-   Tasks CRUD:

    -   Title, description, due date, priority, category/tag

    -   Toggle completion status

-   Task filtering:

    -   Status (All / Completed / Pending)

    -   Category/priority

-   Task search by title/description

**3. Persistent Storage**

-   **Option A:** Firebase Firestore --- real-time updates and per-user tasks

-   **Option B:** Node.js + MongoDB --- associate tasks with user ID

**4. State Management**

-   React **Context API** or **Redux Toolkit** to manage:

    -   Auth state

    -   Task list

    -   UI theme

**5. UI/UX**

-   Responsive design (desktop + mobile)

-   TailwindCSS, Material UI, or Chakra UI

-   Features:

    -   Dark/Light theme toggle

    -   Smooth transitions and animations

**6. Bonus Features (Stretch Goals)**

-   Task reminders / notifications

-   Analytics dashboard (completion %, tasks by category)

-   Calendar view

-   Shared tasks with multiple users
