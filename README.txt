GRADE 10 ROBOTICS LEARNING HUB - PWA PUBLISH PACKAGE

Upload ALL files and folders in this package to the ROOT of a NEW public GitHub repository, then enable GitHub Pages from branch main / root.

The site must be opened once while online over HTTPS. After the first successful load, the app shell and lessons are cached for offline use. On Android Chrome, use the browser menu > Install app (or Add to Home screen). On iPhone Safari, use Share > Add to Home Screen.

The lesson timer, attempts, written responses, and progress are stored locally in the learner's browser/device. They are not sent to a teacher dashboard. Screen visibility monitoring is a limited browser-level deterrent, not a secure kiosk lock. Learners may still use another device or bypass controls.


SCHOOL BRANDING: The app currently displays the school name and a temporary BCNHS text badge. Replace this badge with the official school logo after the school provides the logo image file.
LEARNER PROFILE: Learners enter complete name, grade level, and section. These details are saved locally and included in downloaded lesson answer files and progress reports.


LESSON ACCESS ARRANGEMENT
- Lessons 1 to 6 are open without a code. Learners may review any of these lessons.
- Lesson 6, How Arduino Reads Sensor Data, is the current required lesson.
- Lessons 7 to 12 are protected by individual teacher access codes.
- Codes are embedded in the app and local unlocks are saved on each learner device. This is a classroom pacing gate, not secure authentication. Learners may share codes or inspect offline files.
- Learners should save their complete name, grade level, and section before downloading answers.

TEACHER ACCESS CODES (KEEP PRIVATE)
Lesson 7 - Introduction to Actuators: RBT107
Lesson 8 - Input–Process–Output in Robotics: RBT108
Lesson 9 - Algorithms and Flowcharts: RBT109
Lesson 10 - Introduction to Arduino Programming: RBT110
Lesson 11 - Conditional Statements: RBT111
Lesson 12 - Sensor-Based Project Design: RBT112


INSTALL PROMPT AND APPEARANCE UPDATE
- The app displays an installation guide on first visit and an Install App button.
- On supported Android browsers, the button invokes the browser's native PWA installation prompt.
- If the browser does not offer a native prompt, learners can use Chrome menu > Install app / Add to Home screen. On iPhone, use Safari Share > Add to Home Screen.
- The page background uses a soft light green inspired by DepEd green (#176B45), with the main cards remaining white for readability.
- PWA installation cannot prevent switching to other apps or the phone home screen. The assessment can detect when the page becomes hidden in supported browsers, but only a device-level kiosk/managed-device mode can enforce app lock-down.


OFFICIAL SCHOOL LOGO AND REVIEW MODE UPDATE
- The official Burauen Comprehensive National High School logo is stored at icons/school-logo.png and displayed in the school header.
- The PWA home-screen icons (192px and 512px) have been regenerated using the supplied school logo.
- After the 45-minute timer or screen-switch limit locks a lesson, learner answers are saved locally and the lesson discussion remains visible for review.
- Reopening a previously locked lesson opens it in read-only review mode; answer fields and assessment controls remain disabled.
- Upload/replace the full package contents in the GitHub repository root, including the icons folder, and allow the updated service worker to refresh on learners' devices.
