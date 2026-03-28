# OnlineExams - Mobile Examination System 📱

### **Team Members and  assigned technical roles. **
* **Biruktawit Fiseha** — 0252/15
  * Project Manager + Student Exam Module Developer
    * Responsibilities 1:
                          Create and manage the GitHub repository
                          Invite instructor as collaborator
                          Create professional README.md
                          Ensure all documentation is uploaded in /docs
    * Main Deliverables:
                          GitHub repo setup + README
                          Phase documentation updates
    * Responsibilities 2:
                          Develop Student features:
                                      View available exams
                                      Start exam
                                      Answer questions
                                      Submit exam
                                      Auto-save answers
                                      Handle exam timer countdown
                                      Prevent cheating basics (disable back during exam)
        * Main Deliverables:
                              Exam-taking screen
                              Timer + question navigation
                             Submit exam function
* **Tsinat Zegeye** — 3709/16
  * UI/UX Designer + Frontend Layout Developer
             * Responsibilities:
                          Complete Figma design (wireframes + final UI)
                          Design app navigation flow
                          Create UI screens in Android:
                          Welcome screen
                          Login/Register
                          Dashboard (Student/Instructor)
                          Exam list
                          Profile screen
             * Main Deliverables:
                         Updated Figma board
                         XML layouts / UI components
                         Consistent UI theme and colors
* **Meklit Tesfaye** — 2850/16
   * Firebase Backend Developer
         * Responsibilities:
                          Setup Firebase project
                          Implement Firebase Authentication
                          Login
                          Signup
                          Role-based access (Student/Instructor/Admin)
                          Setup Cloud Firestore database structure
            * Create Firestore collections:
                            users
                            exams
                            questions
                            results
            * Write Firebase security rules
                 * Main Deliverables:
                           Authentication system working
                           Firestore database ready
                           Backend logic for exam storage + results
* **Tibarek Matiwos** — 4062/16
   * Exam Management Module Developer
        * Responsibilities:
                         Develop Instructor features:
                         Create exam
                         Add questions (MCQ / True-False)
                         Set exam time duration
                         Publish exam
                         Save exam data to Firestore
           * Main Deliverables:
                         Exam creation module
                         Question creation module
                         Firestore integration for exams/questions   
* **Nyebuony Mach** — 0661/15
* **Bedane Mengistu** - 1413/16
    * Nyebuony & Bedane - Result & Grading Module Developer + Testing
             * Responsibilities:
                         Implement automatic grading system
                         Store results in Firestore
                         Generate score summary for student
                         Instructor can view student scores
                         Testing the whole app + bug reporting
              * Main Deliverables:
                         Results page
                         Grade calculation logic
                         Instructor result dashboard
                         Testing report + bug fixes

---

## 📌 Project Overview
**OnlineExams** is a mobile application developed as part of the Mobile Application Development (MAD) course at Hawassa University. The platform is designed to streamline the examination process, allowing for secure, real-time quiz creation, student participation, and automated grading.

## 🚀 Phase 1: Resource Links & Documentation

### 1. Project Management (Jira)
We are utilizing the Agile Scrum methodology to track our progress, user stories, and development sprints.
* **Jira Site:** [https://mad-online-exam.atlassian.net/](https://mad-online-exam.atlassian.net/)
* **Status:** Site provisioning and project setup in progress.
* **Note:** The instructor (**eliasjarso@hu.edu.et**) has been invited to the organization for review.

### 2. UI/UX Design (Figma)
Our low-fidelity wireframes outline the core user journey, focusing on intuitive navigation for both students and instructors.
* **Figma Wireframes:** [View Interactive Design](https://www.figma.com/design/XXftKWfnwoUTXaL9NbFZAF/mad-online-exam?node-id=0-1&t=QpQjSpKo52lQXgqQ-1)

### 3. Technical Proposal
A detailed project proposal outlining the problem statement, system architecture, and planned features is available in our documentation folder.
* **[Project Proposal PDF](./docs/Project_Proposal.pdf)**

---

## 🛠 Planned Tech Stack
* **Frontend:** Java (Android Studio)
* **Backend:** Firebase Authentication & Cloud Firestore
* **Version Control:** Git & GitHub
* **Project Management:** Jira Software

---

## 📂 Repository Structure
* `/docs` — Contains the technical proposal and Phase 1 documentation.
* `/app` — (Future) Android Studio project source code.
* `README.md` — Current project overview and resource links.
* `.gitignore` — Standard Android configuration to exclude build artifacts.

---
*Developed for Hawassa University - Department of Information Technology (2026)*
