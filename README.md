# 🎮 TALFBORNE - Game Website

A beautifully designed website for the TALFBORNE student game project, featuring an elegant dark aesthetic with medieval/arcane theming.

## Features

- **Responsive Design** - Works perfectly on desktop, tablet, and mobile
- **Smooth Animations** - Scroll reveal effects and interactive transitions
- **Dark Aesthetic** - Medieval/arcane theme with gold accents and gradient backgrounds
- **Mobile Menu** - Hamburger navigation for smaller screens
- **Gallery** - Showcase game screenshots in an elegant grid layout
- **Team Section** - Display team members and their roles
- **Download Section** - Clear call-to-action for game downloads

## Local Development

### Prerequisites
- Node.js 18+ installed

### Setup

1. Clone the repository:
```bash
git clone <your-repo-url>
cd talfborne
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm start
```

4. Open your browser and visit `http://localhost:3000`

## Deployment on Render

### Step 1: Push to GitHub

1. Initialize git (if not already done):
```bash
git init
git add .
git commit -m "Initial commit: Talfborne website"
git branch -M main
git remote add origin <your-github-repo-url>
git push -u origin main
```

### Step 2: Deploy on Render

1. Go to [render.com](https://render.com)
2. Click **"New +"** and select **"Web Service"**
3. Connect your GitHub repository
4. Choose the repository containing this project
5. Fill in the deployment settings:
   - **Name**: `talfborne`
   - **Environment**: Node
   - **Build Command**: `npm install`
   - **Start Command**: `npm start`
6. Click **"Create Web Service"**
7. Render will automatically build and deploy your site
8. Your site will be live at `https://talfborne.onrender.com` (or your custom domain)

### Step 3: Custom Domain (Optional)

1. In your Render dashboard, go to your service settings
2. Under "Custom Domains", add your domain
3. Follow Render's DNS configuration instructions

## File Structure

```
talfborne/
├── frontend/                  # Frontend files
│   ├── index.html            # Main HTML file
│   └── style.css             # Stylesheet
├── backend/                   # Backend files
│   └── server.js             # Express server
├── package.json              # Dependencies & scripts
├── render.yaml               # Render deployment config
├── .gitignore                # Git ignore file
└── README.md                 # This file
```

## Customization

### Update Content

Edit `index.html` to:
- Change game name and description
- Add team members
- Update feature descriptions
- Add download links

### Modify Styling

Edit `style.css` to:
- Change color scheme (update CSS variables in `:root`)
- Adjust fonts and sizes
- Modify animations and transitions

### Add Images

Place image files in the root directory and reference them in `index.html`:
```html
<div class="shot-bg s1">
  <img src="your-image.jpg" alt="Screenshot description" />
</div>
```

## Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Advanced styling with animations and gradients
- **JavaScript** - Vanilla JS for interactivity (scroll reveals, mobile menu)
- **Express.js** - Lightweight web server

## License

MIT - Feel free to use this template for your projects!

## Support

For issues or questions, please create an issue in the repository or contact the development team.

---

**Status**: Live on Render ✨
