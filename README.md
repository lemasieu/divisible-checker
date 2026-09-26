# Divisible Checker

A simple, interactive web tool that checks whether an integer is divisible by a selected number from 2 to 30. Beyond a simple yes/no answer, it explains the divisibility rule being applied, making it a handy learning aid for students and anyone curious about number theory.

## 🚀 Live Demo

Check out the live demo: [https://www.sieu.io.vn/github/divisible-checker](https://www.sieu.io.vn/github/divisible-checker)

## ✨ Features

- **Divisibility Check (2–30)** – Enter any integer and select a divisor from 2 to 30 to check divisibility
- **Step-by-Step Explanation** – Each result includes the specific divisibility rule used, with the relevant digits or sums shown
- **Reference Table** – A built-in table lists the divisibility rule for each divisor along with a worked example
- **Instant Results** – Results appear immediately after clicking the "OK" button
- **Clean Interface** – Simple, user-friendly design with a clear layout
- **Responsive** – Works on desktop, tablet, and mobile devices

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla)

## 📁 Project Structure

```
divisible-checker/
├── index.html      # Main HTML file
├── style.css       # Stylesheet
├── script.js       # JavaScript divisibility logic
└── README.md       # Project documentation
```

## 🔧 Installation & Usage

1. **Clone the repository**
   ```bash
   git clone https://github.com/lemasieu/divisible-checker.git
   ```
2. **Navigate to the project folder**   
   ```bash
   cd divisible-checker
   ```
3. **Open the application**
   - Simply open `index.html` in your web browser
   - Or use a local development server (e.g., Live Server in VS Code)

## 📝 How It Works

1. **Enter a number** – Type any integer into the input field (negative numbers are supported)
2. **Select a divisor** – Choose a number from 2 to 30 using the dropdown menu
3. **Click "OK"** – The tool checks divisibility and displays the result along with an explanation

**Explanation format:**

For each divisor, the tool applies the corresponding divisibility rule and shows the intermediate steps. For example:

- **Divisor 2**: "The last digit is 4, which is even, so it is divisible by 2."
- **Divisor 3**: "Sum of digits: 15, which is divisible by 3."
- **Divisor 7**: "Remaining part: 48, last digit: 3. 5 × 3 + 48 = 63, which is divisible by 7."
- **Divisor 11**: "Alternating sum: 22, which is divisible by 11."

**Reference Table:**

The page also includes a comprehensive table of divisibility rules for divisors 2 through 30, each with:

- The condition for divisibility
- A sample number
- A worked example demonstrating the rule

## 🤝 Contributing

Contributions are welcome! Feel free to submit a Pull Request or open an Issue.
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License
This project is open-source and available under the MIT License.
