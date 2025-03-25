# 🎨 JS + CSS Variables Project

This is a dynamic visual styling tool built as part of the **JavaScript 30 Challenge (Day 3)**.  
It allows real-time manipulation of CSS variables like spacing, blur, and base color using JavaScript + native HTML inputs.

## 🚀 Features

- 🔧 Live update of CSS custom properties (`--spacing`, `--blur`, `--base-color`)
- 🎨 Color picker that updates styles in **real time** using the `input` event
- 📏 Range sliders for padding and blur effects
- 🖼 Image styled dynamically based on input controls
- 🧼 Clean and responsive UI with scoped CSS variables

## 🛠️ Technologies Used

- **HTML5**
- **CSS3** (with custom properties)
- **Vanilla JavaScript** (no libraries)

## ⚙️ How It Works

Each input has a `name` attribute that matches a CSS variable.  
JavaScript listens to the `input` event and updates the matching variable on `:root` using:

```js
document.documentElement.style.setProperty(`--${this.name}`, this.value + suffix);

## ⚙️ How It Works
Each input has a `name` attribute that matches a CSS variable.
JavaScript listens to the `input` event and updates the matching variable on `:root` using:

document.documentElement.style.setProperty(`--${this.name}`, this.value + suffix);

This makes the image update live as the user interacts with the UI — including real-time color picking.

## 🧠 Key Takeaways
- CSS variables can be manipulated directly with JS
- The input event is more responsive than change or mousemove for interactive UIs
- Real-time interactivity makes even small projects feel polished and fun

## 📸 Preview
(Add a screenshot here: screenshot.png if you have one)

## 📁 How to Run
1. Clone the repo:
   git clone https://github.com/jmurrii-dev/js-css-variables.git

2. Open index.html in your browser.

## 📜 License
This project is open-source and available under the MIT License.

---

🛠 Built by jmurrii-dev | JavaScript 30 - Day 3
```
