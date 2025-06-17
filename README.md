
---

# 🎭 Face Recognition Studio

**Face Recognition Studio** is a modern, responsive web UI for an AI-powered face matching and recognition system. Designed with a sleek dark/light theme, animated backgrounds, and elegant glassmorphism styles, this front-end project simulates a face recognition platform with register/login support and dynamic UX.

- A user uploads a reference image through a web interface.
- The backend scans a large image dataset to find and copy all images containing the same face.
- Face matching is performed using CPU-based Python face recognition (no GPU required).

---

## 🚀 Features

- 🌌 Animated gradient background with floating particles  
- ✨ Glassmorphism and gradient-based UI components  
- 👤 User Registration and Login forms with EmailJS integration  
- 🔄 OTP input fields for secure email verification flow  
- 💡 Light/Dark Theme support  
- 🖼️ Drag-and-drop image upload areas  
- 🔍 Stylish result preview cards with hover animations  
- 📱 Responsive design for mobile and desktop devices

  ### Tolerance Settings Guide
  - **0.4**: Very strict matching (identical twins might not match)
  - **0.6**: Default - good balance of accuracy and recall
  - **0.8**: More lenient (may include similar-looking people)

---

## 📁 Project Structure


📦 Face-Recognition-Studio
- ├── index.html        # Main landing page with image upload & feature cards
- ├── login.html        # Secure login form with OTP verification
- ├── register.html     # User registration page with styled inputs
- ├── home.html         # Home/dashboard page with animated hero sections



---

## 🛠️ Technologies Used

- **HTML5 / CSS3** – For semantic markup and styling  
- **Google Fonts (Inter)** – Sleek modern typography  
- **EmailJS** – Used for sending email OTP (mock logic included)  
- **Vanilla JavaScript** – For UI interactivity (e.g., animations, OTP behavior)  
- **Glassmorphism & Gradient UI Design** – For premium visual experience  

---

## 🔧 Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/face-recognition-studio.git
   cd face-recognition-studio

2. **Run Locally**:
   
   * Open `index.html` in your browser to explore the app.

3. **EmailJS Integration** (Optional):

   * Replace the `emailjs.init("YOUR_PUBLIC_KEY")` in `login.html` and `register.html` with your own [EmailJS](https://www.emailjs.com/) public key.

---

  
## 📸 Preview

> * link *

---

## 📄 License

This project is licensed under the **MIT License**.
Feel free to use, modify, and share it!

---

### 👨‍💻 Built with ❤️ by \HARSH KAKADIYA
