# Code Editor App

A dynamic and feature-rich web-based code editor built using React. This application provides a seamless platform for real-time execution of HTML, CSS, and JavaScript, along with essential developer-friendly features like syntax highlighting, error detection, and intelligent code suggestions.

## Features

- **Real-Time Execution**: Write and execute HTML, CSS, and JavaScript code simultaneously.
- **Syntax Highlighting**: Easily identify different parts of your code with color-coded syntax.
- **Error Detection**: Highlights syntax errors in real time, making debugging more efficient.
- **Code Suggestions**: Auto-completion for commonly used functions and keywords (e.g., typing `con` suggests `console.log`).
- **Screen Management**: Minimize and maximize sections for HTML, CSS, and JavaScript to focus on specific parts of your code.
- **User-Friendly Interface**: A clean, intuitive UI that enhances the coding experience.

## Directory Structure

```
code-editor-app/
├── public/
│   └── index.html
├── src/
│   ├── components/
│   │   ├── App.js
│   │   └── Editor.js
│   ├── Hooks/
│   │   └── useLocalStorage.js
│   ├── index.js
│   └── index.css
├── package.json
└── README.md
```

## Technologies Used

- **Frontend**: React.js
- **State Management**: React Context API
- **Styling**: CSS
- **CodeMirror**: For syntax highlighting and code editing
- **FontAwesome**: For toolbar icons

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/janhavi-j001/code-editor.git
   cd code-editor
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Install required libraries:
   ```bash
   npm install codemirror react-codemirror2 @fortawesome/react-fontawesome @fortawesome/free-solid-svg-icons
   ```

4. Start the development server:
   ```bash
   npm start
   ```

5. Open your browser and navigate to:
   ```
   http://localhost:3000
   ```

## Usage

1. Write your code in the provided HTML, CSS, and JavaScript editors.
2. See the output rendered in real time in the preview pane.
3. Use the syntax suggestions and error highlighting to refine your code.

## Key Dependencies

- `codemirror`: Provides the core editor functionality.
- `react-codemirror2`: React integration for CodeMirror.
- `@fortawesome/react-fontawesome`: React components for FontAwesome icons.
- `@fortawesome/free-solid-svg-icons`: A collection of FontAwesome solid icons.

## Contribution Guidelines

Contributions are welcome! Follow these steps:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m "Description of changes"
   ```
4. Push to your branch:
   ```bash
   git push origin feature-name
   ```
5. Create a pull request.
