# Google Sheets-Like Web Application

## Project Overview
This project is a web application designed to mimic the core functionalities and user interface of Google Sheets. The application enables users to perform data entry, apply basic formatting, and utilize essential mathematical and data quality functions. It aims to deliver a seamless, interactive experience similar to Google Sheets, focusing on usability, accuracy, and performance.

### Goals
- Create a spreadsheet interface with Google Sheets-like UI/UX.
- Provide essential mathematical and data quality functions.
- Ensure interactivity through features like drag-and-drop and cell dependency updates.
- Offer additional functionalities such as saving/loading spreadsheets and data visualization for a comprehensive user experience.

---

## Tech Stack

### Frontend
- **HTML, CSS, JavaScript**: Used for building the core structure, styling, and interactivity of the web application.
- **React.js** *(Optional)*: For creating a dynamic and efficient UI, enabling real-time updates and component-based design.

### Backend (Optional)
- **Node.js**: Can be used for handling server-side logic and data persistence if required.
- **LocalStorage**: Utilized for client-side storage of spreadsheets without requiring a backend.

### Visualization
- **Chart.js**: Integrated for data visualization to create charts and graphs.

---

## Features

### Implemented Functionalities
- **Spreadsheet Interface**:
  - Toolbar and formula bar resembling Google Sheets.
  - Interactive grid structure with editable cells.
  - Ability to add, delete, and resize rows/columns.
  - Drag-and-drop functionality for formulas and cell values.
- **Mathematical Functions**:
  - `SUM`, `AVERAGE`, `MAX`, `MIN`, `COUNT`.
- **Data Quality Functions**:
  - `TRIM`, `UPPER`, `LOWER`, `REMOVE_DUPLICATES`, `FIND_AND_REPLACE`.
- **Data Entry and Validation**:
  - Supports numbers, text, and dates.
  - Basic validation for numeric cells.

### Bonus Features
- Save and load spreadsheets as JSON/CSV files.
- Data visualization with graphs and charts.
- Advanced formula support with relative and absolute referencing.

---

## Instructions

### Setup
1. Clone the repository:
   ```bash
   git clone [repository-link]
   cd [repository-folder]
   ```
2. Open the `index.html` file in a web browser for a standalone version.
3. *(Optional)* If using Node.js, install dependencies and start the server:
   ```bash
   npm install
   npm start
   ```

### Execution
- Open the application in a web browser.
- Interact with the grid by adding, editing, or formatting cells.
- Test mathematical and data quality functions using the formula bar.

### Testing
- Input sample data in the grid and apply functions (e.g., `=SUM(A1:A5)`).
- Verify correct results and proper handling of edge cases (e.g., empty cells).
- Save the spreadsheet, reload the page, and load the saved file.

---

## Code Structure

```
Assignment1/
├── public/
│   ├── index.html      # Main HTML file
│   ├── styles.css      # Styling for the application
│   ├── script.js       # Core JavaScript functionality
│   └── chart.js        # Visualization integration
├── src/
│   ├── components/     # React components (if using React.js)
│   └── utils/          # Utility functions
├── README.md           # Project documentation
└── package.json        # Node.js dependencies (if using Node.js)
```

---

## Non-functional Aspects

### Security Enhancements
- Input validation to prevent injection attacks and ensure safe usage.
- Escaping user inputs in formulas to avoid execution of malicious scripts.

### Performance Optimizations
- Efficient rendering of grid components to ensure smooth interactivity.
- Use of memoization techniques for frequently computed values.
- Asynchronous operations for handling large datasets.

---


