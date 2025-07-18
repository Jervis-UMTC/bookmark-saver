# 📚 Bookmark Saver

A simple, clean, and efficient bookmark manager built with vanilla JavaScript. Save, organize, and manage your favorite websites with persistent local storage.

![Bookmark Saver](https://img.shields.io/badge/Status-Active-brightgreen)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow)
![HTML5](https://img.shields.io/badge/HTML5-orange)
![CSS3](https://img.shields.io/badge/CSS3-blue)

## ✨ Features

- **📖 Add Bookmarks**: Save your favorite websites with custom names
- **🔗 Quick Access**: Click to open bookmarks in new tabs
- **🗑️ Easy Removal**: Remove bookmarks with a single click
- **💾 Persistent Storage**: Bookmarks are saved locally and persist between sessions
- **✅ Input Validation**: Ensures valid URLs and required fields
- **📱 Responsive Design**: Works on desktop and mobile devices
- **🎨 Clean UI**: Modern, minimalist interface with smooth animations

## 🚀 Demo

![Bookmark Saver Demo](demo-screenshot.png)

## 📋 How to Use

1. **Add a Bookmark**:
   - Enter a bookmark name (e.g., "Google")
   - Enter a valid URL (must start with http:// or https://)
   - Click "Add Bookmark"

2. **Access Bookmarks**:
   - Click on any bookmark name to open it in a new tab

3. **Remove Bookmarks**:
   - Click the "Remove" button next to any bookmark

4. **Persistent Storage**:
   - Your bookmarks are automatically saved and will be there when you reload the page

## 🛠️ Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/bookmark-saver.git
   cd bookmark-saver
   ```

2. **Open in browser**:
   ```bash
   # Simply open index.html in your browser
   open index.html
   # or
   double-click index.html
   ```

3. **Or run with a local server** (optional):
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx http-server
   
   # Using Live Server (VS Code extension)
   Right-click index.html → "Open with Live Server"
   ```

## 📁 Project Structure

```
bookmark-saver/
├── index.html          # Main HTML file
├── styles.css          # Styles and responsive design
├── script.js           # JavaScript functionality
└── README.md          # Project documentation
```

## 🔧 Technical Details

### Built With
- **HTML5** - Structure and semantic markup
- **CSS3** - Styling, animations, and responsive design
- **Vanilla JavaScript** - Core functionality and DOM manipulation

### Key Features Implementation
- **Local Storage**: Uses `localStorage` API for data persistence
- **DOM Manipulation**: Dynamic creation and removal of elements
- **Event Handling**: Click events for adding and removing bookmarks
- **Input Validation**: URL format and required field validation
- **Responsive Design**: CSS Flexbox and media queries

### Browser Support
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 🎨 Customization

### Colors
The app uses a green color scheme. To customize:

```css
/* In styles.css, change these variables */
:root {
  --primary-color: #27a567;    /* Main green */
  --primary-hover: #24975e;    /* Darker green for hover */
  --danger-color: #DC3545;     /* Red for remove buttons */
  --background: #F3F4F6;       /* Light gray background */
}
```

### Styling
- Modify `styles.css` to change appearance
- The design uses CSS Grid and Flexbox for layout
- Smooth transitions and hover effects included

## 🔒 Data Storage

- **Storage Method**: Browser's `localStorage`
- **Data Format**: JSON array of bookmark objects
- **Storage Key**: `'bookmarks'`
- **Data Structure**:
  ```javascript
  [
    {
      "name": "Google",
      "url": "https://google.com"
    },
    {
      "name": "GitHub",
      "url": "https://github.com"
    }
  ]
  ```

## 🐛 Known Issues

1. **Filter Logic Bug**: There's a minor bug in the remove function that might affect removal in edge cases
2. **No Duplicate Prevention**: The app doesn't prevent duplicate bookmarks
3. **Limited URL Validation**: Only checks for http:// or https:// prefix

## 🔄 Future Enhancements

- [ ] **Categories/Tags**: Organize bookmarks into categories
- [ ] **Search Functionality**: Search through saved bookmarks
- [ ] **Import/Export**: Import bookmarks from browsers or export to file
- [ ] **Drag & Drop**: Reorder bookmarks by dragging
- [ ] **Edit Bookmarks**: Edit existing bookmark names and URLs
- [ ] **Bulk Operations**: Select multiple bookmarks for batch operations
- [ ] **Dark Mode**: Toggle between light and dark themes
- [ ] **Cloud Sync**: Sync bookmarks across devices

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch**:
   ```bash
   git checkout -b feature/amazing-feature
   ```
3. **Commit your changes**:
   ```bash
   git commit -m 'Add amazing feature'
   ```
4. **Push to the branch**:
   ```bash
   git push origin feature/amazing-feature
   ```
5. **Open a Pull Request**

### Development Guidelines
- Follow existing code style and conventions
- Test your changes thoroughly
- Update documentation as needed
- Keep commits atomic and descriptive

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Your Name**
- GitHub: [@yourusername](https://github.com/yourusername)
- Email: your.email@example.com

## 🙏 Acknowledgments

- Inspired by the need for a simple, lightweight bookmark manager
- Thanks to the web development community for best practices and inspiration
- Built with love for organizing the web! 🌐

## 📊 Stats

![GitHub repo size](https://img.shields.io/github/repo-size/yourusername/bookmark-saver)
![GitHub last commit](https://img.shields.io/github/last-commit/yourusername/bookmark-saver)
![GitHub issues](https://img.shields.io/github/issues/yourusername/bookmark-saver)

---

⭐ **Don't forget to star this repo if you found it useful!** ⭐
