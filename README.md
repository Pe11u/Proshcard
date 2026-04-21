# Proshcard

Proshcard is a simple yet high-performance web-based flashcard and quiz tool. It is optimized for all types of learning, including English vocabulary, terminology memorization, and exam preparation.

Designed to be deployed instantly via GitHub Pages, it requires no installation and allows you to start studying directly from your browser.

---

## Features

* **🎯 Two Learning Modes**:
    * **Multiple Choice**: Speed-focused learning where you select the correct answer from four options.
    * **Typing**: Practical learning where you type out the answer to ensure mastery.
* **🌐 Multilingual Support**: Supports 8 languages: Japanese, English, Korean, Chinese (Simplified/Traditional), Spanish, German, and French.
* **🎨 Modern Design**: Switch between Dark and Light modes. Features a premium, minimalist UI designed for deep focus.
* **🛠 Flexible Customization**:
    * Import/Export card data in JSON format.
    * Configurable question order (Random, Input Order, or Reverse).
    * Flipped learning (swap terms and definitions).
    * Re-challenge logic based on accuracy (customizable maximum retry attempts).
* **⏱ Detailed Time Limits**: Set limits for the overall session or per individual question.
* **📊 Performance Analytics**: View your accuracy rate and a ranking of words you frequently miss.
* **🎵 Audio Feedback**: Visual and auditory feedback for correct and incorrect answers (can be toggled on/off).

---

## How to Use

1.  Open `index.html` in your browser or access the URL published via GitHub Pages.
2.  **Create Presets**: Manually enter terms and definitions using the "Add Card" button, or import a JSON file.
3.  **Configure Settings**: Adjust the number of repetitions, quiz mode, question order, etc., to your preference.
4.  **Start Learning**: Click "Start Learning" to begin!

---

## Import/Export Formats

Card data is managed in a simple text format (via the Raw Editor) or JSON format.

### Text Format (CSV-style)
```text
apple,Apple
banana,Banana
cherry,Cherry
```

### JSON Format (for Import/Export)
```json
{
  "title": "English Vocabulary Lesson 1",
  "cards": [
    { "term": "apple", "definition": "Apple" },
    { "term": "banana", "definition": "Banana" }
  ],
  "settings": {
    "repetitions": 1,
    "quizMode": "both",
    "questionOrder": "random"
  }
}
```

---

## Demo (GitHub Pages)

By uploading this project to your own GitHub repository and enabling GitHub Pages (Settings > Pages > `main` branch), you can instantly build your own personal learning environment.

---

Developed with ❤️ for efficient learning.
