- **NAME:** PARVATHALA SRI KOWSHIK
- **COMPANY:** CODTECH IT SOLUTIONS PRIVATE LIMITED
- **INTERN ID:** CIS255
- **DOMAIN:** EMBEDDED SYSTEMS
- **DURATION:** 6 WEEKS
- **INTERNSHIP PERIOD:** 12TH NOVEMBER 2026 TO 24TH DECEMBER 2026
- **MENTOR:** NEELA SANTHOSH KUMAR

Project Overview
This project simulates a traffic light controller in a web browser using HTML, CSS, and JavaScript. The lights automatically cycle through green, yellow, and red, with a text message showing the current signal.

This version is a browser-based simulation. It does not control physical traffic lights or Arduino hardware.
Features
- Displays red, yellow, and green traffic lights.
- Automatically cycles through the light sequence.
- Shows a status message for each light.
- Runs locally in a web browser without extra software.
Technologies Used
- HTML
- CSS
- JavaScript
Project Files
Smart-Traffic-Light/
└── index.html
How to Run
1. Create a folder named Smart-Traffic-Light.
2. Save the project code in that folder as index.html.
3. Open index.html in a web browser.
4. The traffic light simulation starts automatically.
You can also open the folder in Visual Studio Code and use the Live Server extension to view the page.
Traffic Light Sequence
Signal	Duration	Message
Green	5 seconds	GO — Green light
Yellow	2 seconds	SLOW — Yellow light
Red	5 seconds	STOP — Red light


How It Works
JavaScript stores the signal colors and their durations in a sequence. It turns on the matching light, updates the status message, and uses setTimeout() to move to the next signal. After red, the sequence repeats from green.

CSS styles the lights and changes their appearance when the on class is applied. HTML provides the page structure and the three light elements.
Possible Improvements
- Add pedestrian crossing signals.
- Add a button to request a pedestrian crossing.
- Allow users to adjust light durations.
- Connect a web interface to a microcontroller in a future version.

Output of the project
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/e89c9ab5-7b0c-421b-a9a0-c7159dfe7868" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/21394383-6e53-4800-8305-28dc9042a9c0" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/014e1762-2c0b-4bb1-9786-03dbb155a8d8" />
