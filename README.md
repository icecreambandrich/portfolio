# Personal Portfolio Website

A clean and simple personal portfolio website showcasing your projects and skills.

## How to Customize

### 1. Personal Information
Edit the following sections in `public/index.html`:

**Name and Title** (lines 13-14):
```html
<h1 class="name">Your Name Here</h1>
<p class="title">Your Job Title</p>
```

**About Me Section** (lines 18-27):
- Replace the placeholder text with your own background and interests
- You can add or remove paragraphs as needed

### 2. Projects
Each project is contained in a `project-card` div. To edit a project:

```html
<div class="project-card">
    <h3>Project Title</h3>
    <p>Project description goes here...</p>
    <a href="your-project-link" class="project-link" target="_blank">View Project</a>
</div>
```

**To add a new project:**
1. Copy an existing `project-card` div
2. Update the title, description, and link
3. Paste it inside the `project-grid` div

**To remove a project:**
- Simply delete the entire `project-card` div

### 3. Contact Information
Update the footer links (lines 52-56):
```html
<a href="mailto:your.email@example.com">Email</a>
<a href="https://linkedin.com/in/yourprofile" target="_blank">LinkedIn</a>
<a href="https://github.com/yourusername" target="_blank">GitHub</a>
```

### 4. Colors and Styling
The main colors are defined in `public/styles.css`:
- Primary gradient: `#667eea` to `#764ba2`
- Accent color: `#667eea`
- Text color: `#333`
- Background: `#f8f9fa`

To change colors, search for these hex codes in the CSS file and replace them.

## File Structure
```
portfolio_website/
├── public/
│   ├── index.html      # Main HTML file
│   └── styles.css      # All styling
├── vercel.json         # Vercel configuration
└── README.md           # This file
```

## Features
- ✅ Responsive design (works on mobile and desktop)
- ✅ Clean, modern layout
- ✅ Easy to customize
- ✅ Professional appearance
- ✅ Hover effects and smooth transitions

## Viewing Your Site
Simply open `public/index.html` in your web browser to see your portfolio!

## Tips for Customization
1. Keep project descriptions concise (2-3 sentences)
2. Use high-quality project links (GitHub repos, live demos, etc.)
3. Update the page title in the `<title>` tag
4. Consider adding your own favicon
5. Test on different screen sizes to ensure responsiveness
