# Edge of Bubbles

Interactive bubble portfolio site with natural physics-based stacking effects.

## 🫧 Features

- **Interactive Bubble Physics**: Natural bubble stacking with realistic physics simulation
- **Responsive Design**: Optimized for desktop and mobile devices
- **Smooth Animations**: CSS animations with natural movement and effects
- **Touch & Mouse Support**: Interactive bubble popping on hover and touch
- **Auto-Generation**: Continuous bubble creation with intelligent stacking
- **Natural Decay**: Bubbles naturally disappear over time for performance

## 🚀 Live Demo

[View Live Site](https://your-vercel-url.vercel.app)

## 🛠️ Technology Stack

- **Frontend**: Pure HTML5, CSS3, Vanilla JavaScript
- **Deployment**: Vercel
- **Development**: Node.js with serve for local development

## 📁 Project Structure

```
edge-of-bubbles/
├── index.html          # Main HTML file
├── package.json        # Node.js dependencies and scripts
├── vercel.json         # Vercel deployment configuration
├── .gitignore          # Git ignore rules
└── README.md           # Project documentation
```

## 🔧 Development

### Prerequisites

- Node.js 18+ installed on your system

### Local Development

1. Clone the repository:

   ```bash
   git clone <your-repo-url>
   cd edge-of-bubbles
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the development server:

   ```bash
   npm run dev
   ```

4. Open your browser and navigate to `http://localhost:3000`

### Available Scripts

- `npm run dev` - Start development server
- `npm run start` - Start production server locally
- `npm run preview` - Preview the site
- `npm run build` - Build command (no build step needed for static site)

## 🚀 Deployment

### Deploy to Vercel

1. **Via Vercel CLI:**

   ```bash
   npm install -g vercel
   vercel
   ```

2. **Via GitHub Integration:**

   - Push your code to GitHub
   - Connect your repository to Vercel
   - Automatic deployments on every push to main branch

3. **Via Vercel Dashboard:**
   - Drag and drop your project folder to [Vercel Dashboard](https://vercel.com/dashboard)

### Environment Variables

No environment variables are required for this static site.

## 🎮 How to Use

1. **Bubble Interaction**: Hover over or touch bubbles to make them pop
2. **Physics**: Watch new bubbles push existing ones up as they stack
3. **Natural Flow**: Bubbles will continuously generate and naturally decay
4. **Scroll Effect**: Scrolling the page may cause bubbles to pop

## 🎨 Customization

### Bubble Properties

You can customize bubble behavior by modifying these JavaScript variables in `index.html`:

```javascript
const gravity = 0.5; // Bubble falling speed
const friction = 0.99; // Movement friction
```

### Visual Styling

Bubble appearance can be customized in the CSS:

```css
.bubble {
  /* Modify bubble visual properties */
  background: radial-gradient(/* your gradient */);
  box-shadow: /* your shadow effects */ ;
}
```

## 📱 Browser Support

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- Inspired by natural bubble physics and fluid dynamics
- Built with modern web technologies for optimal performance
