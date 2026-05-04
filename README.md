# Muscle Strength - Workout & Record Planner

This repository contains the project developed for the **Human-Computer Interaction (HCI)** course. The main goal of this project was to apply User-Centered Design (UCD) methodologies to design, prototype, and evaluate a web application focused on fitness, workout planning, and physical progress tracking.

The project is divided into two main components: the logbook detailing the entire UX/UI research process (`/LogBook`) and the functional user interface prototype (`/WebSite`).

## 🚀 Prototype Features (WebSite)

The high-fidelity web prototype was developed using standard front-end technologies (HTML, CSS, JavaScript) and includes the following features:

* **User Authentication:** Login (`login.html`) and Sign Up (`signUp.html`) pages, with local data management (`logins.json`).
* **Workout Management:** Creation of customized workout plans (`Create_Workout_Plan.html`) and detailed view of the plans (`WorkoutPlansDetails.html`).
* **Progress Tracking:** Creation and checking of physical record plans (`Create_Record_Plan.html`, `CheckRecords.html`).
* **Exercise Library:** Exercise catalog (`Exercises.html`) with detailed pages for specific movements such as *Squat*, *Leg Press*, *Bicep Curl*, *Shoulder Press*, among others.
* **Profile Management:** User personal area (`myProfile.html`) and favorites list (`Favourites.html`).
* **Accessibility & Localization:** Support for language selection (`language-dropdown.js`).

## 📂 Repository Structure

### 1. `/WebSite` (Functional Prototype)
Contains all the source code for the user interface:
* `/html`: Structure of the application's pages (including the `/Exercicios` catalog).
* `/css`: Style files organized by components (e.g., `index.css`, `myProfile.css`, `exercises.css`).
* `/js`: Client-side interaction logic (e.g., `CheckRecords.js`, `syncData.js`).
* `/images`: Visual resources and interface assets.
* `/db`: JSON files simulating the system's database.

### 2. `/LogBook` (UX/UI Process)
Documents the entire design lifecycle, from ideation to evaluation:
* **Stage 0 & 1 - Planning and Context:** Problem identification, competitor analysis (e.g., *Darebee*), and user interviews.
* **Stage 2 - Requirements:** Definition of *Personas* and elaboration of use case scenario guides.
* **Stage 3 - Prototyping:** Development of the low-fidelity prototype and task mapping.
* **Evaluation and Usability Testing:** Heuristic evaluation reports and preparation documentation for user testing (Observation guides, consent forms, and post-test questionnaires).

## 🛠️ Technologies Used

* **Front-end:** HTML5, CSS3, Vanilla JavaScript.
* **Storage (Mock):** JSON.
* **Documentation:** Markdown (`.md`), Microsoft Word (`.docx` for test scripts).

## 👥 Team

Project developed by:
* Francisco
* Hugo
* Pedro

## ⚙️ How to Run the Project

To view the prototype, no complex server installation or dependencies are required:
1. Clone this repository or download the `/WebSite` folder.
2. Open the `index.html` file directly in your preferred web browser.
3. Navigate through the interface to simulate the user journey.
