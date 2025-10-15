Duration-Based Countdown Timer

A simple, easy-to-use countdown timer built with vanilla JavaScript, HTML, and CSS. It counts down from a set duration (default 5 minutes) showing minutes and seconds, updating every second. When the timer reaches zero, it displays a “Time’s up!” message.

Features

Countdown from a fixed duration (default: 5 minutes)

Real-time update of minutes and seconds

Start button to initiate the countdown

Timer stops automatically when time expires

User-friendly and responsive design

How to Use

Open index.html in any modern web browser.

Click the Start Timer button to begin counting down.

Watch the timer update every second.

When the timer hits zero, the message “⏰ Time’s up!” appears.

Customize Timer Duration

To change the countdown duration, open script.js and modify this line:

let countdownDuration = 5 * 60; // 5 minutes (change the number as needed)


For example, to set it to 10 minutes:

let countdownDuration = 10 * 60;

Project Structure
/project-root
├── index.html     # The main HTML page
├── style.css      # CSS styles for the timer
└── script.js      # JavaScript countdown logic

Requirements

No dependencies. Works in all modern browsers with JavaScript enabled.

License

This project is free to use and modify.
