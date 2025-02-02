# ⏰ Digital Clock

A simple and stylish digital clock created using **HTML**, **CSS**, and **JavaScript**.

## 🕒 Features
- Displays the current time in `HH:MM:SS` format.
- Updates every second in real-time.
- Minimal and responsive design.

## 🗒 Preview
![Clock Preview](https://harjotrocks.com/javascript/digital-clock/)

## 🛠️ How to Use
1. Clone or download this repository.
2. Open `index.html` in any modern web browser.

## 📚 Code Explanation
### HTML Structure
The basic structure consists of a container to display hours, minutes, and seconds:
```html
<div class="clock">
  <span id="hrs">00</span> :
  <span id="min">00</span> :
  <span id="sec">00</span>
</div>
```

### JavaScript Logic
The clock updates every second using `setInterval()` and the `Date` object:
```javascript
setInterval(() => {
  let currentTime = new Date();
  hrs.innerHTML = (currentTime.getHours() < 10 ? "0" : "") + currentTime.getHours();
  min.innerHTML = (currentTime.getMinutes() < 10 ? "0" : "") + currentTime.getMinutes();
  sec.innerHTML = (currentTime.getSeconds() < 10 ? "0" : "") + currentTime.getSeconds();
}, 1000);
```

## ✨ Demo
You can see the clock in action by opening `index.html` directly in your browser.

## 🌐 Technologies Used
- HTML5
- CSS3
- JavaScript ES6

## 🛠️ Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/Harjot2552/digital-clock.git
   ```
2. Navigate to the project directory and open `index.html`.

## ❤️ Contribution
Feel free to submit issues or pull requests to improve this project.


