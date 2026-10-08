# Thai Name Generator 🇹🇭

สร้างชื่อไทย ชื่ออังกฤษ และชื่อเล่น

**Thai Name Generator** - A web application to randomly generate Thai names, English names, and nicknames.

## Features ✨

- 🎯 **Multiple Gender Options**: ชาย (Male), หญิง (Female), ไม่ระบุ (Unisex)
- 🎨 **Multiple Styles**: 
  - คลาสสิก (Classic)
  - ทันสมัย (Modern)
  - น่ารัก (Cute)
  - หรูหรา (Royal)
- 🔤 **Three Name Types**:
  - Thai Name (ชื่อไทย)
  - English Name (ชื่ออังกฤษ)
  - Nickname (ชื่อเล่น)
- 📱 **Responsive Design**: Works on desktop and mobile devices
- ⚡ **Fast & Lightweight**: No dependencies, pure HTML/CSS/JS

## Tech Stack 🛠️

- **Frontend**: HTML5, CSS3, JavaScript (ES6 Modules)
- **Deployment**: Vercel / GitHub Pages
- **Data**: External JS module (`data/names.js`)

## Project Structure 📁

```
thai-name-generator/
├── index.html          # Main HTML page
├── data/
│   └── names.js        # Name data (ES6 export)
├── package.json        # Project metadata
├── vercel.json         # Vercel configuration
├── .gitignore          # Git ignore rules
└── README.md           # This file
```

## How to Use 🚀

### Online
Visit: https://thainame-generator.vercel.app

### Local Development

1. Clone the repository:
```bash
git clone https://github.com/Thivabc/thai-name-generator.git
cd thai-name-generator
```

2. Open `index.html` in your browser:
   - On macOS: `open index.html`
   - On Windows: Double-click `index.html`
   - Or use a local server: `python -m http.server 8000`

## Development 💻

### Adding More Names

Edit `data/names.js` and add your names to the appropriate category:

```javascript
export const thaiNames = {
  male: {
    classic: ["Name1", "Name2", "Name3", ...],
    modern: ["Name1", "Name2", ...],
    cute: ["Name1", "Name2", ...],
    royal: ["Name1", "Name2", ...]
  },
  // ... other categories
};
```

### Customizing Styles

Edit the CSS in `index.html` `<style>` tag:

```css
:root {
  --primary: #2563eb;      /* Button color */
  --primary-dark: #1d4ed8; /* Button hover color */
  --bg: #f8fafc;           /* Background */
  --panel: #ffffff;        /* Card background */
}
```

## Deployment 🌐

### Vercel (Recommended)

1. Push your changes to GitHub
2. Connect your repo to Vercel at https://vercel.com
3. Vercel will auto-deploy on every push

### GitHub Pages

1. Go to Repository Settings
2. Enable GitHub Pages
3. Select `main` branch as source
4. Site will be available at `https://username.github.io/thai-name-generator`

## Browser Support 🌍

- Chrome/Edge: ✅ Latest
- Firefox: ✅ Latest
- Safari: ✅ Latest
- Mobile browsers: ✅ iOS Safari, Chrome Mobile

## License 📄

MIT License - feel free to use this project for any purpose

## Author 👤

Created by [@Thivabc](https://github.com/Thivabc)

---

**Enjoy creating Thai names!** 🎉
