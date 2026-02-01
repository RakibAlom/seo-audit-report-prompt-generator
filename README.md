# 🔍 Website Audit Report Prompt Generator

A sophisticated web-based tool designed for digital marketing agencies and SEO professionals to generate structured, AI-ready prompts for creating comprehensive website audit reports. Transform raw audit data into persuasive, professional reports that convert prospects into clients.

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat&logo=tailwind-css&logoColor=white)

## ✨ Features

### Multi-Section Audit Input
- **9 Comprehensive Sections** covering every aspect of website auditing
- **Progress Tracking** with visual progress bar
- **Tab-based Navigation** for easy section switching
- **Auto-save friendly** form structure

### Core Audit Categories

1. **Basic Information** - Client details, industry, agency branding, audit date
2. **Performance Scores** - Desktop/mobile speed, load times, page size
3. **Core Web Vitals** - LCP, FID, and CLS metrics with status indicators
4. **SEO Issues** - Meta tags, headings, alt text, broken links, sitemap/robots.txt status
5. **Mobile & Security** - Mobile friendliness, SSL certificates, security headers, mixed content
6. **Content Analysis** - Thin content detection, duplicate content, orphan pages
7. **Additional Issues** - Dynamic issue adding with custom entries
8. **Custom Fields** - Extensible custom findings with preset templates (Accessibility, UX/UI, Conversion, Branding, Technical, Analytics, Local SEO, Social Media)
9. **Competitor Comparison** - Benchmarking against competitors with Domain Authority comparison
10. **Report Preferences** - Tone customization, length control, visual suggestions, pricing sections

### Smart Features

- **Preset Templates**: One-click addition of common audit categories (Accessibility, UX/UI, Conversion Optimization, etc.)
- **Character Counters**: Real-time character counting for text areas
- **Dynamic Fields**: Add/remove additional issues and custom fields on the fly
- **Glassmorphism UI**: Modern, visually appealing interface with gradient effects
- **Responsive Design**: Fully functional on desktop, tablet, and mobile devices
- **Export Options**: Copy to clipboard or download as .txt file

## 🚀 How to Use

### Getting Started
1. Open `index.html` in any modern web browser
2. The tool works offline - no internet connection required after initial load
3. Default date is automatically set to today

### Step-by-Step Workflow

#### 1. Basic Information
- Enter client business name and website URL
- Specify industry vertical
- Add your agency branding
- Set audit date (defaults to today)

#### 2. Performance Scores
- Input Google PageSpeed scores (0-100) for Desktop and Mobile
- Enter page load time and total page size
- Fill in **Core Web Vitals**:
  - **LCP** (Largest Contentful Paint): Measures loading performance
  - **FID** (First Input Delay): Measures interactivity
  - **CLS** (Cumulative Layout Shift): Measures visual stability
- Select status for each metric (Good/Needs Improvement/Poor)

#### 3. SEO Issues
- Count missing meta titles and descriptions
- Identify missing/duplicate H1 tags
- Track missing image alt attributes
- Log broken links (404s) and redirect chains
- Indicate sitemap.xml and robots.txt status

#### 4. Mobile & Security
- Confirm mobile-friendliness (Yes/No)
- Describe any mobile usability issues
- Check SSL certificate validity
- Note mixed content warnings
- Review security headers status

#### 5. Content Issues
- Count pages with thin content (&lt;300 words)
- Document duplicate content instances
- Identify orphan pages (no internal links)

#### 6. Additional Issues
- Add quick one-off issues found during audit
- Use the "+" button to add multiple issues
- Remove issues with the trash icon

#### 7. Custom Fields ⭐
This is where the tool shines for detailed findings:

**Manual Addition:**
- Click "Add New Custom Field"
- Enter field title (e.g., "Accessibility Issues")
- Add detailed description with findings

**Quick Presets:**
Use the preset buttons for instant common categories:
- 🎨 **Accessibility** - WCAG compliance, ARIA labels, contrast issues
- 🖌️ **UX/UI Problems** - Navigation, CTAs, layout issues
- 📈 **Conversion Optimization** - Forms, trust signals, checkout flow
- 🎭 **Branding Consistency** - Logo usage, colors, typography
- 💻 **Technical Debt** - Outdated plugins, deprecated code
- 📊 **Analytics & Tracking** - GA setup, event tracking, heatmaps
- 📍 **Local SEO Issues** - NAP consistency, Google Business Profile
- 🔗 **Social Media Integration** - Open Graph tags, social links

#### 8. Competitor Comparison
- Enter competitor URL and their metrics
- Compare Domain Authority scores
- Document their speed scores for benchmarking

#### 9. Report Preferences
- **Tone**: Professional, Friendly, or Formal
- **Length**: Short (5 pages), Medium (8 pages), or Detailed (10+ pages)
- **Visuals**: Include visual suggestions for charts/graphs
- **Pricing**: Optionally include service pricing section
- **Extra Instructions**: Add specific directions for the AI (e.g., "Focus heavily on technical SEO")

### Generating the Prompt

1. Navigate through all sections using "Next" or section tabs
2. On the last section, click **"Generate Prompt"**
3. Review the structured output in the results area
4. **Copy** to clipboard or **Download** as text file
5. Paste into ChatGPT, Claude, or your preferred AI assistant

## 🎯 Generated Report Structure

The tool creates a comprehensive prompt that instructs AI to generate:

- **Executive Summary** with overall health score
- **Color-coded Scoring** (Green/Yellow/Red system)
- **Section-by-Section Findings** organized by category
- **Priority Recommendations** with quick wins highlighted
- **Professional Call-to-Action** for your agency services
- **Visual Suggestions** for charts and comparisons
- **Strategic Recommendations** without giving away full implementation details (perfect for lead generation)

## 🛠️ Technical Details

### Tech Stack
- **HTML5** - Semantic markup
- **Tailwind CSS** (via CDN) - Utility-first styling
- **Vanilla JavaScript** - No frameworks required
- **Font Awesome** - Iconography
- **Google Fonts** (Inter) - Typography

### Browser Compatibility
- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+
- Mobile browsers (iOS Safari, Chrome Mobile)

### File Structure
website-audit-prompt-generator/
├── index.html          # Main application file (self-contained)
└── README.md          # Documentation

*Note: This is a single-file application. All CSS and JavaScript are embedded in the HTML for easy portability.*

## 🎨 Customization

### Changing Colors
The tool uses CSS custom properties for the glassmorphism effects. Key classes to modify:
- `.gradient-text` - Main gradient colors (currently purple/pink)
- `.btn-primary` - Primary button gradients
- `.glass-card` - Card background transparency
- `.floating-orb` - Background ambient orbs