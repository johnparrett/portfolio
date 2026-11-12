# Portfolio Website

A clean, responsive personal portfolio website showcasing web development projects and services.

## Quick Start

### Option 1: Open Files Directly (Simplest)
1. Clone the repository:
   ```bash
   git clone https://github.com/johnparrett/portfolio.git
   cd portfolio
   ```

2. Open `index.html` in your web browser:
   - **macOS/Linux**: `open index.html`
   - **Windows**: `start index.html`
   - Or simply drag `index.html` into your browser

### Option 2: Use a Local Development Server (Recommended)

#### Using Python (Built-in)
```bash
# Python 3.x
python3 -m http.server 8000

# Python 2.x
python -m SimpleHTTPServer 8000
```
Then visit: `http://localhost:8000`

#### Using Node.js
1. Install http-server globally:
   ```bash
   npm install -g http-server
   ```

2. Run the server:
   ```bash
   http-server
   ```
Then visit: `http://localhost:8080`

#### Using VS Code Live Server Extension
1. Install the "Live Server" extension in VS Code
2. Right-click on `index.html` and select "Open with Live Server"
3. The site will open automatically in your default browser

#### Using macOS with Python (One-liner)
```bash
cd portfolio && python3 -m http.server 8000 && open http://localhost:8000
```

## Project Structure

```
portfolio/
├── index.html          # Home page
├── about.html          # About page with bio
├── work.html           # Portfolio/work samples with slideshow
├── contact.html        # Contact information
├── style.css           # Main stylesheet
├── query.style.css     # Responsive media queries
├── assets/             # Images and portfolio screenshots
└── README.md           # This file
```

## Features

- **Responsive Design**: Mobile-friendly layout that works on all screen sizes
- **Portfolio Slideshow**: Interactive carousel showcasing project work
- **SEO Optimized**: Proper meta tags and Open Graph tags for social sharing
- **Accessible**: Semantic HTML with alt text for images
- **Dark Theme**: Professional black and white color scheme with red accents

## Technologies Used

- HTML5
- CSS3 (with media queries for responsiveness)
- Vanilla JavaScript (slideshow navigation)

## Customization

### Update Your Information
- Edit `about.html` to update your bio and skills
- Edit `contact.html` to change contact information
- Update the email link in `contact.html` to your email address

### Add Portfolio Projects
1. Add project images to the `assets/` folder
2. Edit `work.html` and add a new slide:
   ```html
   <div class="w3-display-container mySlides">
       <img src="assets/your-project.png" style="width:100%">
       <a href="https://your-project-url.com" target="_blank">
           <div class="w3-display-bottomleft w3-large w3-container w3-padding-16 w3-black">
               Your Project Name
           </div>
       </a>
   </div>
   ```

### Customize Colors
Edit `style.css` to change the color scheme:
- Red accent color: `#D0312D`
- Background: `black`
- Text: `white`

## Deployment

### GitHub Pages
1. Push your changes to GitHub
2. Go to repository Settings → Pages
3. Select `main` branch as the source
4. Your site will be live at `https://username.github.io/portfolio`

### Other Hosting
- **Netlify**: Drag and drop the `portfolio` folder to deploy
- **Vercel**: Connect your GitHub repo for automatic deployments
- **Traditional Hosting**: Upload all files via FTP/SFTP

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Development Notes

- No build process required—pure HTML/CSS/JS
- No dependencies to install
- All external resources (fonts, icons) are loaded from CDNs
- Images are optimized for web use

## License

This portfolio is custom built. Feel free to use it as a template for your own portfolio!

---

For questions or to discuss collaboration, visit the contact page or reach out via email.
