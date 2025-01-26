# Daily JavaScript App - Day 28: Digital Clock ⏰  

A simple yet elegant **Digital Clock** application designed to showcase the current time dynamically. Part of my **Daily JavaScript Coding Challenge**, this project focuses on creating a visually appealing and responsive time display.  

## ✨ Features  
- **Real-Time Update:** Displays live hours, minutes, and seconds.  
- **Responsive Design:** Ensures an optimized user experience across all devices.  
- **Modern UI:** Styled with gradients, transparency, and smooth edges for an aesthetically pleasing look.  

---

## 📂 File Structure  
```  
├── index.html          # Main HTML file  
├── style.css           # CSS file for styling  
└── app.js              # JavaScript file for dynamic functionality  
```  

---

## 📋 Technologies Used  
- **HTML5** 🏗️: For structuring the webpage.  
- **CSS3** 🎨: For styling and creating a visually stunning design.  
- **JavaScript** ⚡: For implementing live clock functionality.  

---

## 🚀 How It Works  
The clock dynamically updates the current time every second using JavaScript's `setInterval()` method. The `Date` object retrieves the system time, and custom formatting ensures two-digit numbers for a sleek display.  

---

## 🖥️ Preview  
### Desktop View  
The clock floats elegantly at the center of the screen, enhanced by a vibrant gradient background and soft shadows.  

### Mobile View  
Responsive design ensures the clock adjusts seamlessly to fit smaller screens without losing its charm.  

---

## 🔧 How to Use  
1. Clone or download the project files to your local machine:  
   ```bash  
   git clone https://github.com/enesatacan/Digital-Clock  
   ```  
2. Open the `index.html` file in any modern web browser.  
3. Watch the clock come to life!  

---

## 💻 Code Highlights  
### HTML  
A clean and structured layout for the clock:  
```html  
<div class="clock">  
  <span id="hrs">00</span>:  
  <span id="min">00</span>:  
  <span id="sec">00</span>  
</div>  
```  

### CSS  
Modern styles with gradients, transparency, and animations:  
```css  
.hero {  
  background: linear-gradient(45deg, #08001f, #30197d);  
  color: white;  
}  

.clock {  
  background: rgba(234, 0, 255, 0.11);  
  backdrop-filter: blur(40px);  
}  
```  

### JavaScript  
Dynamic updates using the `setInterval()` function:  
```javascript  
setInterval(() => {  
  let currentTime = new Date();  
  hrs.innerHTML = (currentTime.getHours() < 10 ? "0" : "") + currentTime.getHours();  
  min.innerHTML = (currentTime.getMinutes() < 10 ? "0" : "") + currentTime.getMinutes();  
  sec.innerHTML = (currentTime.getSeconds() < 10 ? "0" : "") + currentTime.getSeconds();  
}, 1000);  
```  

---

## 🌟 About the Project  
This project is part of my **Daily JavaScript Coding Challenge**, where I challenge myself to build a new project every day. The goal is to enhance my problem-solving skills, refine my design sense, and become a more consistent developer.  

---

## Screenshot

![image](https://github.com/user-attachments/assets/9cb70e56-6a25-4d2c-9b5a-4306f61586a4)
