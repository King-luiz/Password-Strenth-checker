# Password-Strength Checker

## 📋 Project Overview
The **Password-Strength Checker** is a simple web-based tool designed to help users evaluate the strength of their passwords in real-time. It visually indicates whether a password is weak, moderate, or strong, encouraging better password security practices.

## 🚀 Features
- **Real-Time Password Strength Detection**: Instantly checks password strength as you type.
- **Visual Feedback**: Displays a colored strength meter with labels (Weak, Moderate, Strong).
- **Password Visibility Toggle**: Allows users to show or hide the password while typing.

## 🛠️ Technologies Used
- **HTML5** - For structuring the web page.
- **CSS3** - For styling the layout and the strength meter.
- **JavaScript (Vanilla)** - For password strength logic and interactivity.

## 📂 Project Structure
```
Password-Strength-Checker/
├── index.html       # Main HTML file
├── style.css        # CSS file for styling
└── script.js        # JavaScript file for functionality
```

## 🔑 How It Works
1. **Password Input:** Users enter their password into the input field.
2. **Strength Evaluation:** The password is evaluated based on the following criteria:
   - Password length (6+ and 10+ characters)
   - Inclusion of uppercase letters
   - Inclusion of numbers
   - Use of both letters and numbers
3. **Visual Feedback:** A colored strength meter appears:
   - **Red (Weak):** Low strength (1-2 points)
   - **Yellow (Moderate):** Medium strength (3-4 points)
   - **Green (Strong):** High strength (5+ points)
4. **Toggle Visibility:** The "Show/Hide" button allows users to toggle password visibility.

## 💡 Usage Instructions
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/Password-Strength-Checker.git
   ```
2. **Open the Project:**
   - Navigate to the project folder.
   - Open `index.html` in your preferred browser.
3. **Test:**
   - Enter various passwords and observe the strength meter.
   - Use the "Show/Hide" button to toggle password visibility.

## 📊 Password Strength Logic
The password strength is determined by accumulating points for each of the following:
- Password length greater than 6 characters
- Password length greater than or equal to 10 characters
- Contains uppercase letters
- Contains numbers
- Contains both letters and numbers

## ✅ To-Do (Future Enhancements)
- Add support for special characters in strength evaluation.
- Display tips for creating stronger passwords.
- Implement animations for smoother transitions.
- Make it mobile-responsive.

## 🤝 Contributing
Contributions are welcome! If you'd like to improve this project:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a Pull Request.

   ## Demo


https://github.com/user-attachments/assets/f020eef0-95b2-4922-9fc9-ff90307cdce3


   

## 📄 License
This project is licensed under the [MIT License](LICENSE).

---

**Made with ❤️ for better password security!**

