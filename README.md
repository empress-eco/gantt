<div align="center">
    <img src="https://grow.empress.eco/uploads/default/original/2X/1/1f1e1044d3864269d2a613577edb9763890422ab.png" height="128">
    <h1 align="center">Empress Gantt: Interactive Gantt Chart Library for the Modern Web</h1>
    <p align="center">
        Enhance your project management efficiency with interactive, customizable Gantt charts.
        <br />
        <a href="https://grow.empress.eco/">Explore the Docs</a>
        ·
        <a href="https://github.com/empress-eco/gantt/issues">Report Bug</a>
        ·
        <a href="https://github.com/empress-eco/gantt/issues">Request Feature</a>
    </p>
</div>

## About The Project

### 📖 Overview
Empress Gantt is a modern, interactive Gantt chart library designed for the web. It provides developers with a powerful tool to visualize project timelines, making project management more efficient and visually appealing.

### 🌟 Key Features
- **Interactive Gantt Charts:** Implement drag-and-drop functionality to adjust tasks easily.
- **Customizable Options:** Personalize the look of your Gantt chart to match your project needs.
- **Multilingual Support:** Ideal for managing international projects with multiple language support.

### 🛠 Technical Stack
Empress Gantt is built with the following major framework:
- [JavaScript](https://www.javascript.com/)

## Getting Started

### Prerequisites
Before installing Empress Gantt, ensure [Node.js](https://nodejs.org/) is installed on your system.

### Installation
Follow these steps to incorporate the Gantt library into your project:

1. Open your terminal and navigate to your project directory.

2. Install the Gantt library using npm by executing the following command:
```sh
npm install Empress-gantt
```
3. Include the Gantt library in your HTML file:
```HTML
<script src="Empress-gantt.min.js"></script>
<link rel="stylesheet" href="Empress-gantt.css">
```
4. Start creating your Gantt charts. Here's a quick start guide:
```js
var tasks = [
  {
    id: 'Task 1',
    name: 'Redesign website',
    start: '2016-12-28',
    end: '2016-12-31',
    progress: 20,
    dependencies: 'Task 2, Task 3',
    custom_class: 'bar-milestone' // optional
  },
  /* ... */
]
var gantt = new Gantt("#gantt", tasks);
```
## Contributing

We appreciate your interest in contributing to our project! Follow these steps to contribute:

1. Fork the Project on GitHub.
2. Create a feature branch: `git checkout -b feature/AmazingFeature`.
3. Commit your changes: `git commit -m 'Add some AmazingFeature'`.
4. Push to the branch: `git push origin feature/AmazingFeature`.
5. Open a pull request.

## License and Acknowledgements

### License
This project is licensed under the MIT License. Any contributions you make are also licensed under the MIT License.

### Acknowledgements
We express our profound gratitude to the [Empress Community](https://github.com/Empress) for maintaining the foundational tools that drive this project. Their innovative efforts and continuous support have made a significant impact. Thank you for your dedication and pioneering work.