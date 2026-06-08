# jack the ripper · Random Data Generator Suite

A sleek, glass‑morphic web toolset for developers and designers: generate **test credit card numbers** (Luhn‑valid) and **lorem ipsum placeholder text** on the fly. Both tools share a unified dark glass interface, smooth page transitions, and fully responsive layout.

<img width="1919" height="878" alt="Screenshot 2026-06-09 030534" src="https://github.com/user-attachments/assets/061077c5-0dcd-4b22-9b96-f1915bb07254" />


## 🚀 Features

### 💳 Credit Card Generator
- Generates valid test credit card numbers using the **Luhn algorithm**.
- Custom BIN (Bank Identification Number) support.
- Optional **expiry date** (month/year) and **CVV** – can be random or fixed.
- Batch generation (up to any quantity).
- Multiple output formats: `CHECKER` (pipe‑separated), `JSON`, `PIPE`.
- **Custom format** field for advanced patterns (e.g. `410039003911xxxx|09|2099|rnd`).

### 📝 Lorem Ipsum Generator
- Generate dummy text by **characters, words, sentences, or paragraphs**.
- Adjustable count via slider or number input.
- Instant copy‑to‑clipboard.
- Clean, classic Latin corpus with rich vocabulary.

### 🌐 General
- **Identical top bar** on both pages: logo + “Generate CC” / “Generate Lorem” buttons for seamless navigation.
- **Footer links**: About, Contact, Privacy Policy – with dedicated pages and a “←” back button to return to the main tool.
- **Glassmorphic dark theme** – frosted glass cards, blur effects, neon blue accents.
- **Fade‑in animation** when switching between pages.
- Fully responsive – works on desktop, tablet, and mobile.

## 📁 Project Structure
```
├── index.html # Credit Card Generator (main page)
├── lorem.html # Lorem Ipsum Generator
├── cc_img_01.jpg # Logo image (used in header)
└── README.md # This file
```


## 🔧 Installation & Usage

1. **Clone the repository**  
   ```bash
   git clone https://github.com/yourusername/jack-the-ripper.git
   cd jack-the-ripper
   ```

   ### ⚠️ Disclaimer
   
- Educational & Testing Purpose Only

- The credit card numbers generated are not real and have no monetary value. They are produced solely for testing payment gateways, e‑commerce sandboxes, and educational demonstrations.

- Do not use these numbers for any illegal or fraudulent activity. The author assumes no liability for misuse.

- The Lorem Ipsum text is standard placeholder dummy text and is free to use in any design or development project.

### 🛠️ Technologies Used

- HTML5 / CSS3
- JavaScript (ES6)
- jQuery (for DOM manipulation)
- Google Fonts (Poppins)
- CSS Grid / Flexbox – Glassmorphism effects (backdrop‑filter, radial gradients)

