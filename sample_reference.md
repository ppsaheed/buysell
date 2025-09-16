# UAE's online classifieds  - Website


## 🌟 Features

- **Modern Design**: Clean, professional UAE-inspired design with gold accents
- **Responsive**: Fully responsive design that works on all devices
- **Fast Performance**: Built with Vite + React for optimal performance
- **SEO Optimized**: Proper meta tags and semantic HTML structure
- **Accessible**: ARIA labels and keyboard navigation support
- **Interactive**: Smooth animations and hover effects

## 🚀 Quick Start

### Prerequisites

- Node.js (version 16 or higher)
- npm or yarn package manager

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd Dubuynsell
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and visit `http://localhost:5173`

## 📦 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build locally
- `npm run lint` - Run ESLint for code quality
- `npm run deploy` - Deploy to GitHub Pages

## 🏗️ Project Structure

```
src/
├── components/          # Reusable UI components
│   ├── Navbar.jsx      # Navigation component
│   ├── Footer.jsx      # Footer component
│   └── ServiceCard.jsx # Service display component
├── pages/              # Page components
│   ├── Home.jsx        # Homepage
│   ├── Services.jsx    # Services listing page
│   └── Contact.jsx     # Contact page
├── data/               # Data and content
│   └── services.js     # Company and services data
├── App.jsx             # Main app component
├── main.jsx           # App entry point
└── index.css          # Global styles and Tailwind imports
```

- Social media links
- WhatsApp and phone quick actions



## 🚀 Deployment

### GitHub Pages (Recommended)

1. Push your code to a GitHub repository
2. Enable GitHub Pages in repository settings
3. The GitHub Action will automatically deploy on push to main branch

### Manual Deployment

1. Build the project:
```bash
npm run build
```

2. Upload the `dist` folder contents to your web server

### Environment Configuration

For different deployment environments, update the `base` path in `vite.config.js`:

```javascript
// For GitHub Pages
base: '/repository-name/'

// For custom domain
base: '/'
```

## 🔧 Customization

### Adding New Services
1. Edit `src/data/services.js`
2. Add new service object to `servicesData`
3. Update service categories in `Services.jsx` if needed

### Styling Changes
- Global styles: `src/index.css`
- Tailwind config: `tailwind.config.js`
- Component-specific styles: Use Tailwind classes

### Content Updates
- Company information: `src/data/services.js` - `companyInfo` object
- Success story: `src/data/services.js` - `storyContent` object

## 📞 Contact Information

dubuynsell.com
📞 +971 54 994 5431
https://www.instagram.com/dubuynsell
