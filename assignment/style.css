const minutesEl = document.getElementById('minutes');
const secondsEl = document.getElementById('seconds');
const messageEl = document.getElementById('message');
const startBtn = document.getElementById('startBtn');

let countdownDuration = 5 * 60; // 5 minutes in seconds
let countdownInterval;

function formatTime(num) {
  return num < 10 ? '0' + num : num;
}

function updateTimer(secondsLeft) {
  const mins = Math.floor(secondsLeft / 60);
  const secs = secondsLeft % 60;

  minutesEl.textContent = formatTime(mins);
  secondsEl.textContent = formatTime(secs);
}

function startCountdown() {
  clearInterval(countdownInterval);
  let timeLeft = countdownDuration;

  updateTimer(timeLeft);
  messageEl.textContent = '';

  countdownInterval = setInterval(() => {
    timeLeft--;

    if (timeLeft < 0) {
      clearInterval(countdownInterval);
      messageEl.textContent = "⏰ Time's up!";
      return;
    }

    updateTimer(timeLeft);
  }, 1000);
}

startBtn.addEventListener('click', startCountdown);
