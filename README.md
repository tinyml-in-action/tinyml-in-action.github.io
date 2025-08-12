# TinyML: A Compact Revolution in Engineering AI

**MERCon 2025 Workshop**

A static website for the TinyML workshop organized by BrAIN Labs research group at SLIIT. This workshop introduces participants to Tiny Machine Learning concepts, model compression techniques, and embedded AI deployment.

## 🚀 Quick Start

### Prerequisites
- [VS Code](https://code.visualstudio.com/) installed
- Live Server extension for VS Code

### Setup Instructions

1. **Clone or Download** this repository
2. **Open VS Code** and open the project folder
3. **Install Live Server Extension:**
   - Press `Ctrl+Shift+X` (Extensions)
   - Search "Live Server"
   - Install the one by **Ritwick Dey**
4. **Launch the website:**
   - Right-click on `index.html`
   - Select **"Open with Live Server"**
   - Your browser will automatically open the website

## 📁 Project Structure

```
tinyml-workshop/
├── index.html          # Main website file
├── README.md          # This file
└── assets/            # Future assets (images, documents)
    └── (empty for now)
```

## 🎨 Customization Guide

### Editing Content

All content is contained in `index.html`. The website uses a clean, academic layout similar to GitHub Pages Cayman theme.

#### Key Sections to Edit:

**1. Workshop Title & Tagline**
```html
<h1 class="project-name">TinyML: A Compact Revolution in Engineering AI</h1>
<h2 class="project-tagline">MERCon 2025</h2>
```

**2. Navigation Buttons**
```html
<a href="#home" class="btn">Home</a>
<a href="#accepted-papers" class="btn">Accepted Papers</a>
<!-- Add/remove buttons as needed -->
```

**3. Workshop Summary**
```html
<h2 id="workshop-summary">Workshop summary</h2>
<p>Your workshop description here...</p>
```

**4. Organizers Table**
```html
<tbody>
    <tr>
        <td><strong>Dr. Name</strong></td>
        <td>Position</td>
        <td>Institution</td>
        <td>email@domain.com</td>
    </tr>
    <!-- Add/remove rows as needed -->
</tbody>
```

### Styling Changes

The website uses inline CSS for easy editing. Key style variables:

- **Primary Color**: `#159957` (green theme)
- **Link Color**: `#1e6bb8` (blue)
- **Text Color**: `#606c71` (gray)

To change colors, search and replace these hex values in the `<style>` section.

### Adding New Sections

```html
<h2 id="new-section">New Section Title</h2>
<p>Section content here...</p>
```

Don't forget to add corresponding navigation button:
```html
<a href="#new-section" class="btn">New Section</a>
```

## 📱 Responsive Design

The website is fully responsive and works on:
- ✅ Desktop computers
- ✅ Tablets
- ✅ Mobile phones

## 🛠️ Features

- **Clean Academic Layout**: Matches GitHub Pages Cayman theme
- **Smooth Scrolling Navigation**: Click buttons to jump to sections
- **Professional Typography**: Uses Open Sans font
- **Mobile Responsive**: Works on all device sizes
- **No Dependencies**: Self-contained HTML file
- **Easy Editing**: All content in one file for VS Code editing

## 📧 Workshop Information

**Organizers**: BrAIN Labs research group at SLIIT  
**Primary Contact**: asiri.l@sliit.lk  
**Conference**: MERCon 2025  
**Format**: Hybrid (Physical + Online)

## 📝 Workshop Topics

- Model Compression Techniques
- Quantization-Aware Training
- Knowledge Distillation
- Embedded AI Deployment
- TensorFlow Lite for Microcontrollers
- Hardware Platforms (Arduino, ESP32, Raspberry Pi)

## 🤝 Contributing

To make changes:

1. Edit `index.html` in VS Code
2. Save the file
3. Live Server will automatically refresh your browser
4. No build process or server setup required!

## 📄 License

This project is open source. Feel free to use and modify for your own academic workshops.

## 🔗 Links

- **BrAIN Labs**: Research group at SLIIT
- **MERCon 2025**: Main conference website (TBA)
- **Contact**: asiri.l@sliit.lk

---

**Built with ❤️ for the TinyML community**
