GRADE 10 ROBOTICS LEARNING HUB — VERSION 11 (PWA)
Burauen Comprehensive National High School | Burauen, Leyte

IMPORTANT: HOW TO INSTALL
1. Extract this ZIP file on your computer.
2. Upload ALL files and folders inside the extracted folder to the ROOT of your GitHub repository (replace the old files). Keep index.html in the root and keep the icons folder.
3. In GitHub, open Settings > Pages and confirm deployment from branch main / root.
4. Wait for GitHub Pages deployment. Open the published HTTPS website (for this project: https://analyn2026.github.io/grade10-robotics-learning-hub/).
5. On Android, open that HTTPS link in Chrome > menu (⋮) > Install app or Add to Home screen. On iPhone, open in Safari > Share > Add to Home Screen.

A local file opened as file:///.../index.html is ONLY a computer preview. It cannot be installed as a Progressive Web App. Version 11 now displays this explanation when opened locally. PWA installation requires a published HTTPS website (or localhost for development). The app cannot silently install itself; the user must confirm using the browser's install option.

OFFLINE USE
Open the published website while connected to the internet and wait for it to finish loading. The service worker then caches the app shell, icons, and embedded lesson content. After successful caching, the hub can be reopened offline on that same browser/device. Reconnect occasionally to receive updates. Offline use is not guaranteed before the first successful online load.

WHAT THE HUB COVERS — 12 LESSONS
1. Introduction to Robotics — meaning, purpose, examples, and uses of robots.
2. Basic Components of a Robot — sensors, controller, actuators, and power source.
3. Introduction to Arduino Uno — board overview, purpose, and basic pins/components.
4. Introduction to Sensors — what sensors do and how robots use input.
5. Types of Arduino Sensors — examples such as LDR, push button, ultrasonic, PIR, and temperature/humidity sensors.
6. How Arduino Reads Sensor Data — digital and analog input, readings, and interpreting sensor data. This is the current required lesson.
7. Introduction to Actuators — output devices such as LEDs, buzzers, and motors.
8. Input–Process–Output in Robotics — how a robot receives input, processes it, and performs an output/action.
9. Algorithms and Flowcharts — planning step-by-step solutions and representing logic.
10. Introduction to Arduino Programming — basic program structure and introductory Arduino commands.
11. Conditional Statements — using if/else logic to make decisions.
12. Sensor-Based Project Design — planning a simple sensor-based robotics solution.

LEARNER FEATURES
- Learner profile: complete name, grade level, and section.
- Twelve lessons; Lessons 1–6 are open for review. Lesson 6 is the current required lesson.
- Lessons 7–12 require teacher-provided access codes.
- Each lesson includes lesson notes, examples/visual guides, written activities, interactive knowledge checks, and reflection.
- 45-minute lesson answering session; maximum of two assessment attempts.
- Learner answers and progress are stored locally on that device/browser. They can be downloaded for submission.
- When a session is locked, answers remain saved and lesson discussion can be reviewed in read-only mode.

TEACHER ACCESS CODES — KEEP PRIVATE
Lesson 7: RBT107
Lesson 8: RBT108
Lesson 9: RBT109
Lesson 10: RBT110
Lesson 11: RBT111
Lesson 12: RBT112

IMPORTANT LIMITATIONS
- The hub is a learning and assessment support tool, not a replacement for teacher instruction or physical robotics practice.
- No Arduino hardware kit or programming software is required for the lessons as currently designed; students learn concepts and work through guided activities.
- Learner records are local to each browser/device and do not automatically sync to a central teacher dashboard.
- Screen-switch monitoring is a browser-level deterrent only. It cannot fully lock a phone or prevent switching to other apps. Use device-level kiosk/managed-device controls if strict lockdown is required.
- Access codes are a classroom pacing gate, not secure authentication; learners may share or inspect codes in offline files.

SCHOOL BRANDING
The school logo is stored in icons/school-logo.png and used in the school header and generated app icons.

VERSION 12 — OFFLINE ASSESSMENT ATTEMPT RECORDS
- Assessment attempt count is stored in a per-lesson local record in the browser's localStorage.
- A new attempt is counted when the learner begins the assessment; the selected answer is saved immediately after each response.
- The current question and saved responses are restored if the learner reloads or closes/reopens the hub in the same browser/device while an attempt is active.
- Completing an attempt records it as completed. A second attempt may be started only if fewer than two attempts have been used. After two attempts, the assessment remains locked for that lesson on that browser/device.
- The record is designed to work offline after the PWA has been successfully cached.
- Teacher Summary remains device-local; the learner should download/export the work for teacher review.

ATTEMPT-RECORD LIMITATIONS
- These are client-side records, not tamper-proof records. Clearing site/browser data, using private browsing, another browser, or another device can reset or create a separate attempt history.
- Offline devices cannot send records to a central teacher dashboard. For centrally enforced attempts and reliable teacher reporting, the hub would need an online backend and learner authentication.
