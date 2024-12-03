
# Kid-Friendly Analog and Digital Clock

![Clock Screenshot](screenshot.png)

Welcome to the **Kid-Friendly Analog and Digital Clock** project! This application showcases both an analog and a digital clock side by side, designed with bright colors and clear visuals to engage and educate children about time-telling.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Demo](#demo)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running the Application](#running-the-application)
- [HTA Compliance](#hta-compliance)
  - [What is HTA?](#what-is-hta)
  - [Running as an HTA](#running-as-an-hta)
- [Project Structure](#project-structure)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Introduction

The **Kid-Friendly Analog and Digital Clock** is a simple yet effective web application that displays the current time in both analog and digital formats. The analog clock features large, colorful hands and numbers to make learning time enjoyable for children. The digital clock provides a clear numerical representation of the current time, enhancing time-telling skills.

Originally developed as a standard web application, this project has been adapted to be **HTA (HTML Application)** compliant, allowing it to run as a standalone application on Windows systems with enhanced functionality.

## Features

- **Dual Display:** Showcases both analog and digital clocks side by side.
- **Kid-Friendly Design:** Bright colors, large numbers, and clear fonts make it appealing and easy to read for children.
- **Responsive Layout:** Adjusts gracefully to different screen sizes and window states.
- **Smooth Animations:** Clock hands move smoothly to represent the passing of time accurately.
- **HTA Compatibility:** Can be run as a standalone HTA application on Windows.

## Demo

![Clock Demo](demo.gif)

*Note: Replace the above placeholders with actual images or GIFs of your clock in action.*

## Getting Started

### Prerequisites

To run the **Kid-Friendly Analog and Digital Clock**, you need:

- A modern web browser (e.g., Chrome, Firefox, Edge) for the standard web version.
- For the HTA version:
  - A Windows operating system.
  - Internet Explorer installed (HTA relies on IE's rendering engine).

### Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/kid-friendly-clock.git
   ```

2. **Navigate to the Project Directory:**

   ```bash
   cd kid-friendly-clock
   ```

### Running the Application

#### Standard Web Version

1. **Open the HTML File:**

   Locate the `index.html` file in the project directory.

2. **Launch in Browser:**

   Double-click `index.html` or right-click and select your preferred web browser to view the clock.

#### HTA Version

1. **Ensure HTA Support:**

   Make sure your Windows system supports HTA applications. HTA is supported on Windows systems with Internet Explorer installed.

2. **Save as HTA:**

   - Open the `index.html` file in a text editor (e.g., Notepad).
   - Save the file with an `.hta` extension, for example, `clock.hta`.

3. **Run the HTA Application:**

   - Navigate to the saved `clock.hta` file.
   - Double-click the file to launch it as a standalone application.

## HTA Compliance

### What is HTA?

**HTA (HTML Application)** is a Microsoft Windows feature that allows HTML, CSS, and JavaScript to run as standalone applications with greater access to the Windows system. HTA applications run with higher privileges compared to standard web pages, making them suitable for desktop applications that require deeper system integration.

### Running as an HTA

To ensure compatibility with HTA:

- **JavaScript Compatibility:** Replaced modern JavaScript features (`const`, `let`, `querySelector`) with older equivalents (`var`, `getElementById`).
- **Script Tag Adjustments:** Specified the scripting language explicitly to ensure proper interpretation.
- **Element Selection:** Assigned unique `id` attributes to clock hands for selection using `getElementById`.
- **CSS Adjustments:** Added vendor prefixes where necessary to support older IE versions.

**Note:** HTA relies on the older Internet Explorer rendering engine, which may have limited support for some modern CSS features. Ensure that your system's IE version is compatible.

## Project Structure

```
kid-friendly-clock/
├── index.html         # Main HTML file for the web version
├── clock.hta          # HTA-compliant version of the clock
├── styles.css         # External CSS (if separated)
├── script.js          # External JavaScript (if separated)
├── README.md          # Project documentation
└── assets/
    ├── screenshot.png  # Screenshot of the clock
    └── demo.gif        # GIF demonstrating clock functionality
```

*Note: Adjust the structure based on your actual project setup.*

## Customization

You can customize the clock's appearance and functionality by modifying the HTML, CSS, and JavaScript files.

### Changing Colors

- **Clock Face:** Modify the `background` property in the `#analog-clock` CSS selector.
- **Clock Hands:** Adjust the `background` colors in `.hour-hand`, `.minute-hand`, and `.second-hand` classes.
- **Digital Clock:** Change the `color` and `text-shadow` properties in the `#digital-clock` class.

### Adjusting Sizes

- **Clock Size:** Change the `width` and `height` properties in the `#analog-clock` selector.
- **Hand Lengths:** Modify the `height` properties in the `.hour-hand`, `.minute-hand`, and `.second-hand` classes.
- **Number Size:** Adjust the `font-size` and `width`/`height` in the `.number` class.

### Adding Features

- **Alarm Functionality:** Integrate audio alerts that trigger at specific times.
- **Themes:** Create multiple themes (e.g., dark mode) and allow users to switch between them.
- **Interactive Learning:** Add tooltips or clickable elements to teach children about time.

## Contributing

Contributions are welcome! Whether it's reporting bugs, suggesting features, or submitting pull requests, your input is valuable.

1. **Fork the Repository:**

   Click the **Fork** button at the top right of the repository page.

2. **Create a Feature Branch:**

   ```bash
   git checkout -b feature/YourFeatureName
   ```

3. **Commit Your Changes:**

   ```bash
   git commit -m "Add Your Feature"
   ```

4. **Push to the Branch:**

   ```bash
   git push origin feature/YourFeatureName
   ```

5. **Open a Pull Request:**

   Navigate to your forked repository and click **New Pull Request**.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

- Inspired by the need to create educational and engaging tools for children.
- Thanks to the open-source community for providing resources and support.
- Thanks to ChatGPT o1-mini (src: https://chatgpt.com/share/674f0526-e510-800b-a97b-797bc1fafed0)
- 
---


