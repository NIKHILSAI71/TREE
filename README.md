# 📁 Folder Tree Generator

A simple, elegant web application that generates visual folder tree structures from your local directories. Perfect for documentation, project overviews, or sharing folder structures with others.

## ✨ Features

- **Drag & Drop Interface**: Simply drag and drop any folder onto the interface
- **File Browser Support**: Use the "Choose Folder" button to browse and select directories
- **Visual Tree Structure**: Generates clean, hierarchical folder trees with proper ASCII art
- **Copy to Clipboard**: One-click copying of the generated tree structure
- **File & Folder Count**: Shows total number of files and folders processed
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Real-time Processing**: Instant tree generation as you select folders

## 🚀 Demo

[Live Demo](https://nikhilsai71.github.io/TREE/) *(Replace with your actual GitHub Pages URL)*

## 🖼️ Preview

The application generates folder trees like this:
```
project-folder:
├───src:
│   ├───components:
│   │   ├───Button.jsx
│   │   └───Modal.jsx
│   ├───utils:
│   │   └───helpers.js
│   └───index.js
├───public:
│   ├───index.html
│   └───favicon.ico
└───package.json
```

## 🛠️ Technologies Used

- **HTML5** - Structure and semantics
- **CSS3** - Styling and responsive design
- **Vanilla JavaScript** - Core functionality and file processing
- **Font Awesome** - Icons for better UX
- **File System Access API** - For folder selection and processing

## 🔧 Installation & Usage

### Online Usage
1. Visit the [live demo](https://nikhilsai71.github.io/TREE/)
2. Drag and drop a folder or click "Choose Folder"
3. View the generated tree structure
4. Click "Copy" to copy the tree to your clipboard

### Local Development
1. Clone the repository:
   ```bash
   git clone https://github.com/NIKHILSAI71/TREE.git
   ```
2. Navigate to the project directory:
   ```bash
   cd TREE
   ```
3. Open `FolderTree.html` in your web browser

## 📂 Project Structure

```
TREE/
├───FolderTree.html    # Main HTML file
├───script.js          # JavaScript functionality
├───styles.css         # CSS styles
├───.github/
│   └───workflows/
│       └───deploy.yml # GitHub Pages deployment
└───README.md          # Project documentation
```

## 🌟 Key Features Breakdown

### File Processing
- Handles both drag-and-drop and file input selection
- Processes directories recursively
- Maintains proper folder hierarchy
- Sorts folders before files alphabetically

### User Interface
- Clean, minimalist design
- Responsive layout for all screen sizes
- Visual feedback for drag-and-drop operations
- Toast notifications for user actions

### Tree Generation
- ASCII art tree structure
- Proper indentation and connectors
- Folder and file differentiation
- Maintains directory structure integrity

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature-name`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin feature-name`
5. Submit a pull request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👤 Author

**NIKHILSAI71**
- GitHub: [@NIKHILSAI71](https://github.com/NIKHILSAI71)
- Profile: [GitHub Profile](https://github.com/NIKHILSAI71)

## 🐛 Bug Reports & Feature Requests

If you encounter any bugs or have feature requests, please [create an issue](https://github.com/NIKHILSAI71/TREE/issues) on GitHub.

## 🔄 Changelog

### v1.0.0
- Initial release
- Basic folder tree generation
- Drag and drop functionality
- Copy to clipboard feature
- Responsive design implementation

---

⭐ **Star this repository if you find it useful!**
