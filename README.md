# SheetsClone

A modern, React-based spreadsheet application that mimics core Google Sheets functionality. Built with React, TypeScript, and Tailwind CSS.

![SheetsClone Screenshot](https://images.unsplash.com/photo-1537432376769-00f5c2f4c8d2?auto=format&fit=crop&q=80&w=1000)

## 🌟 Features

### 📊 Spreadsheet Interface
- Google Sheets-inspired UI with toolbar, formula bar, and cell structure
- Interactive cell selection and editing
- Support for basic cell formatting (bold, italics)
- Real-time formula evaluation

### 🧮 Mathematical Functions
- `SUM()`: Calculate the sum of cell ranges
- `AVERAGE()`: Calculate the average of cell ranges
- `MAX()`: Find the maximum value in a range
- `MIN()`: Find the minimum value in a range
- `COUNT()`: Count numerical values in a range

### 🔍 Data Quality Functions
- `TRIM()`: Remove leading/trailing whitespace
- `UPPER()`: Convert text to uppercase
- `LOWER()`: Convert text to lowercase

## 🚀 Getting Started

### Prerequisites
- Node.js (v18 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/harshammg/SheetsClone.git
```

2. Install dependencies:
```bash
cd SheetsClone
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:5173`

## 🛠️ Built With
- [React](https://reactjs.org/) - UI Framework
- [TypeScript](https://www.typescriptlang.org/) - Programming Language
- [Tailwind CSS](https://tailwindcss.com/) - Styling
- [Zustand](https://github.com/pmndrs/zustand) - State Management
- [Lucide React](https://lucide.dev/) - Icons
- [DND Kit](https://dndkit.com/) - Drag and Drop

## 📝 Usage

### Basic Cell Editing
1. Click on any cell to select it
2. Type your content or formula
3. Press Enter to confirm

### Using Formulas
Start with an equals sign (=) followed by the function name and arguments:
```
=SUM(A1,A2)
=AVERAGE(B1,B2,B3)
=MAX(C1:C10)
```

### Formatting
Use the toolbar buttons to:
- Toggle bold text
- Toggle italic text
- Change text alignment
- Modify font properties

## 🤝 Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🌐 Live Demo
Check out the live demo: [SheetsClone Demo](https://adorable-torrone-73628f.netlify.app)

## 🙏 Acknowledgments
- Inspired by Google Sheets
- Built with modern web technologies
- Open source community and contributors
