# DSAI-SEED Project Website - GitHub Hosting Guide

## Repository Setup Instructions

### 1. Create GitHub Repository
1. Go to GitHub.com and create a new repository
2. Name it: `dsai-seed-project` (or any preferred name)
3. Make it public for GitHub Pages hosting
4. Initialize with README (optional)

### 2. Upload Website Files
Upload all files from the `/home/ubuntu/dsai-seed-website/` directory:

**Required Files:**
- `index.html` - Main website file
- `styles.css` - Stylesheet
- `script.js` - JavaScript functionality
- `images/` folder with all extracted images:
  - `image-000.png` (header element)
  - `image-001.png` (Thapar Institute logo)
  - `image-002.png` (Workflow diagram - Figure 1)
  - `image-003.png` (Patient workflow - Figure 2)
  - `image-004.png` (Project Gantt chart)
  - `image-005.png` (blank image)

### 3. Enable GitHub Pages
1. Go to repository Settings
2. Scroll to "Pages" section
3. Select "Deploy from a branch"
4. Choose "main" branch and "/ (root)" folder
5. Click Save

### 4. Access Your Website
- Your website will be available at: `https://[username].github.io/[repository-name]/`
- It may take a few minutes to deploy initially

## File Structure
```
dsai-seed-website/
├── index.html          # Main HTML file
├── styles.css          # CSS stylesheet
├── script.js           # JavaScript functionality
├── images/             # Image assets folder
│   ├── image-001.png   # Thapar logo
│   ├── image-002.png   # Workflow diagram
│   ├── image-003.png   # Patient workflow
│   └── image-004.png   # Gantt chart
└── README.md           # Optional documentation
```

## Website Features
- **Responsive Design**: Works on desktop and mobile devices
- **Professional Styling**: Medical/healthcare theme with blue color scheme
- **Interactive Elements**: Smooth scrolling, hover effects, animations
- **Content Sections**:
  - Hero section with project overview
  - About section with challenge/solution
  - Research framework with PDF diagrams
  - Team section with all investigators
  - Timeline with project milestones
  - Impact and contact sections

## Technical Specifications
- **Framework**: Pure HTML5, CSS3, JavaScript (ES6)
- **Fonts**: Inter (Google Fonts)
- **Icons**: Font Awesome 6.0
- **Layout**: CSS Grid and Flexbox
- **Compatibility**: Modern browsers (Chrome, Firefox, Safari, Edge)
- **Performance**: Optimized images and minimal dependencies

## Maintenance
- All content is extracted from the original PDF proposal
- Images are properly optimized for web use
- No external dependencies except CDN resources
- Easy to update content by editing HTML file

## Contact Information
- **Institution**: Thapar Institute of Engineering and Technology
- **Department**: Centre of Excellence in Data Science and AI
- **Project Duration**: 24 months (April 2025 - March 2027)
- **Budget**: ₹48.65 Lakhs

