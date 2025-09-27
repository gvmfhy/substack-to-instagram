# Substack to Instagram Carousel Generator

Transform your long-form content into beautiful Instagram carousel images. Perfect for writers, content creators, and anyone who wants to repurpose their essays for social media.

## 🎯 Features

- **Smart Text Splitting**: Automatically chunks your content into Instagram-friendly slides
- **Multiple Formats**: Support for Portrait (4:5), Square (1:1), and Story (9:16)
- **Beautiful Design**: Clean, readable typography with elegant gradients
- **Batch Export**: Download individual slides or all at once as a ZIP
- **No Dependencies**: Pure HTML/CSS/JavaScript - works in any modern browser

## 🚀 Quick Start

### Option 1: Use Online
Visit the live demo: [https://gvmfhy.github.io/substack-to-instagram](https://gvmfhy.github.io/substack-to-instagram)

### Option 2: Run Locally
1. Download `index.html`
2. Open it in your browser
3. Start converting!

## 📝 How to Use

1. **Paste Your Content**: Copy your Substack post or any long-form text
2. **Generate Slides**: Click "Generate Slides" to auto-split into carousel format
3. **Navigate**: Use arrow keys or click dots to preview each slide
4. **Download**: Export individual slides or download all as ZIP

## 🎨 Slide Specifications

- **Portrait (4:5)**: 1080×1350px - Best for feed posts (~320 chars/slide)
- **Square (1:1)**: 1080×1080px - Classic Instagram (~280 chars/slide)
- **Story (9:16)**: 1080×1920px - Full screen stories (~400 chars/slide)

## 💡 Tips for Best Results

- Keep paragraphs concise for better readability
- The tool respects your original paragraph breaks
- Add line breaks between major ideas
- Review and adjust text before generating

## 🛠️ Customization

### Quick Setup - Change Your Blog/Social Handle

Find this line in `index.html` (around line 376):
```javascript
const authorHandle = "@yourusername"; // ← Edit this!
```
Change `@yourusername` to your blog name or social handle (e.g., `"austinpatrick.substack.com"` or `"@yourhandle"`).

### Advanced Customization

Want to customize colors, fonts, or branding? Edit these sections in `index.html`:

```javascript
// Background gradient colors (lines ~455-457)
gradient.addColorStop(0, '#fefcfb');
gradient.addColorStop(0.5, '#fef9f5');
gradient.addColorStop(1, '#fef6f0');

// Font settings (line ~495)
ctx.font = `${fontSize}px Georgia, serif`;

// Text color (line ~469)
ctx.fillStyle = '#1f2937';
```

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest features
- Submit pull requests

## 📄 License

MIT License - feel free to use this tool for any purpose!

## 🙏 Credits

Created by [Austin Morrissey](https://austinpatrick.substack.com)

Built with assistance from Claude AI

---

**Found this useful?** Give it a ⭐ on GitHub!