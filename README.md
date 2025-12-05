# Student Access Benefits Portal

> A comprehensive directory of **90+ free and discounted tech resources** for students pursuing AI, Computer Science, and related fields — including the complete GitHub Student Developer Pack.

[![GitHub Pages](https://img.shields.io/badge/Hosted%20on-GitHub%20Pages-blue?logo=github)](https://github.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

---

## Overview

Students often miss out on thousands of dollars worth of free software, cloud credits, and professional tools simply because they don't know these benefits exist. This portal solves that problem by providing a single, searchable directory of all available student benefits.

```
┌────────────────────────────────────────────────────────────────┐
│                  STUDENT ACCESS BENEFITS PORTAL                │
├────────────────────────────────────────────────────────────────┤
│                                                                │
│  ┌────────┐┌────────┐┌────────┐┌────────┐┌────────┐┌────────┐ │
│  │   AI   ││  Dev   ││ Cloud  ││ Design ││Discount││ GitHub │ │
│  │ Tools  ││ Tools  ││Platform││ Tools  ││ & Deal ││  Pack  │ │
│  └───┬────┘└───┬────┘└───┬────┘└───┬────┘└───┬────┘└───┬────┘ │
│      │         │         │         │         │         │      │
│      ▼         ▼         ▼         ▼         ▼         ▼      │
│   ┌─────────────────────────────────────────────────────────┐ │
│   │              90+ Curated Resources                      │ │
│   │                                                         │  │
│   │  • Step-by-step activation guides                       │  │
│   │  • Verification requirements                            │  │
│   │  • Direct links to student programs                     │  │
│   │  • Value estimates & duration                           │  │
│   └─────────────────────────────────────────────────────────┘  │
│                                                                │
└────────────────────────────────────────────────────────────────┘
```

---

## Features

| Feature | Description |
|---------|-------------|
| **Search** | Instantly filter resources by name, category, or keyword |
| **Dark Mode** | Eye-friendly dark theme with system preference detection |
| **Detailed Guides** | Step-by-step instructions for claiming each benefit |
| **Categories** | 8 organized tabs for easy navigation |
| **GitHub Pack** | Complete GitHub Student Developer Pack with 50+ tools |
| **Responsive** | Works on desktop, tablet, and mobile |
| **No Backend** | Pure HTML/CSS/JS - fast and privacy-friendly |

---

## Categories

### AI Tools
GitHub Copilot, Google Gemini, Perplexity Pro, ChatGPT Plus, Weights & Biases, Hugging Face, Deepnote

### Developer Tools
GitHub Student Pack, JetBrains Suite, Termius, GitKraken, PopSQL, Namecheap, DigitalOcean

### Cloud Platforms
Microsoft Azure ($100), AWS Educate, Google Cloud, Oracle Cloud Free Tier, SageMaker Studio Lab

### Design & Creative
Figma, Canva Pro, Autodesk Suite, Unity Student, MATLAB Academic

### Productivity
Notion, Microsoft 365, Tableau Student, Educative, DataCamp

### Discounts & Deals
Apple, Samsung, Spotify + Hulu, Notebooksbilliger (Germany), UNiDAYS

### GitHub Student Developer Pack
The complete pack in one dedicated tab with organized subcategories:
- **Core GitHub Tools**: GitHub Pro, Copilot, Codespaces
- **IDEs & Dev Tools**: JetBrains, VS Code Packs, Tower, GitKraken, Termius, PopSQL
- **Cloud & Infrastructure**: Azure, DigitalOcean, Heroku, MongoDB, Appwrite, LocalStack
- **Learning Platforms**: Frontend Masters, DataCamp, Educative, Scrimba, GoRails
- **Domains & Hosting**: Namecheap, Name.com, .TECH domains
- **Security & DevOps**: 1Password, Doppler, Sentry, New Relic, Datadog, Travis CI
- **Design & Productivity**: Icons8, Bootstrap Studio, Notion, PomoDone, Visme
- **Hardware & IoT**: Arduino Cloud, Adafruit IO+
- **APIs & Testing**: Stripe, LambdaTest, BrowserStack, Testmail, Bump.sh, Imgbot

---

## Architecture

```
*
│
├── index.html          # Single-page application (HTML + CSS + JS)
├── README.md           # This documentation
│
└── Structure inside index.html:
    │
    ├── <style>         # Embedded CSS with CSS variables
    │   ├── Light/Dark theme definitions
    │   ├── Responsive grid layouts
    │   ├── Card and modal components
    │   └── Animation keyframes
    │
    ├── <body>          # Semantic HTML structure
    │   ├── Header (logo, search, theme toggle)
    │   ├── Tab navigation
    │   ├── Tab content sections
    │   │   ├── About/Getting Started
    │   │   ├── AI Tools
    │   │   ├── Developer Tools
    │   │   ├── Cloud Platforms
    │   │   ├── Design Tools
    │   │   ├── Productivity
    │   │   ├── Discounts
    │   │   └── GitHub Pack (with subcategories)
    │   ├── Guide modals
    │   └── Footer
    │
    └── <script>        # Vanilla JavaScript
        ├── Theme switching logic
        ├── Tab navigation
        ├── Search functionality
        ├── Modal management
        └── Guide content database
```

---

## Verification Methods

Most student benefits require verification. Here's how the main verification services work:

```
┌──────────────────────────────────────────────────────────────────┐
│                    VERIFICATION FLOW                             │
└──────────────────────────────────────────────────────────────────┘
                              │
        ┌─────────────────────┼─────────────────────┐
        │                     │                     │
        ▼                     ▼                     ▼
┌───────────────┐     ┌───────────────┐     ┌───────────────┐
│   SheerID     │     │   UNiDAYS     │     │  .edu Email   │
│               │     │               │     │               │
│ • Instant     │     │ • One-time    │     │ • Direct      │
│ • Document    │     │   sign-up     │     │   verification│
│   upload      │     │ • App-based   │     │ • Fastest     │
│ • 3-5 min     │     │ • UK/EU focus │     │   method      │
└───────────────┘     └───────────────┘     └───────────────┘
        │                     │                     │
        └─────────────────────┼─────────────────────┘
                              │
                              ▼
                    ┌─────────────────┐
                    │  Access Granted │
                    │   to Benefits   │
                    └─────────────────┘
```

**Accepted Documents:**
- Student ID card
- Enrollment letter
- Class schedule
- Tuition receipt
- University email (.edu or institution domain)

---

## Quick Start

### Option 1: GitHub Pages (Recommended)
Simply fork this repository and enable GitHub Pages in settings. Your portal will be live at:
```
https://[your-username].github.io/free-ai-credits/
```

### Option 2: Local Development
```bash
# Clone the repository
git clone https://github.com/[your-username]/free-ai-credits.git

# Navigate to directory
cd free-ai-credits

# Open in browser (macOS)
open index.html

# Or use a local server
python -m http.server 8000
# Then visit http://localhost:8000
```

---

## Estimated Value

| Category | Approximate Annual Value |
|----------|-------------------------|
| Cloud Credits | $1,500+ (Azure, AWS, GCP, DigitalOcean, Heroku) |
| Development Tools | $1,000+ (JetBrains, GitHub Pro, GitKraken, Tower) |
| AI Tools | $500+ (Copilot, Perplexity Pro, Gemini) |
| Design Software | $1,000+ (Autodesk, Figma, Bootstrap Studio) |
| Learning Platforms | $600+ (Frontend Masters, DataCamp, Educative) |
| DevOps & Monitoring | $4,000+ (New Relic, Datadog, Sentry) |
| GitHub Pack Total | $13,000+ (all pack benefits combined) |
| **Total** | **$10,000+ per year** |

---

## Contributing

Contributions are welcome! If you know of a student benefit not listed here:

1. Fork the repository
2. Add the new resource following the existing card format
3. Include a guide modal with step-by-step instructions
4. Submit a pull request

### Card Format Example
```html
<div class="card" data-search="keywords for search">
    <div class="card-main">
        <div class="card-header">
            <div class="card-logo [category]">[emoji]</div>
            <span class="card-badge badge-free">BADGE TEXT</span>
        </div>
        <h3 class="card-title">Tool Name</h3>
        <p class="card-description">Brief description of the benefit.</p>
        <div class="card-tags">
            <span class="tag">tag1</span>
            <span class="tag">tag2</span>
        </div>
    </div>
    <div class="card-footer">
        <span class="card-value">Value description</span>
        <button class="btn-guide" onclick="openGuide('toolkey')">
            View Guide →
        </button>
    </div>
</div>
```

---

## Tech Stack

- **HTML5** - Semantic markup
- **CSS3** - Custom properties, Grid, Flexbox, animations
- **Vanilla JavaScript** - No dependencies, fast loading
- **Google Fonts** - Plus Jakarta Sans, JetBrains Mono

---

## License

MIT License - feel free to use, modify, and distribute.

---

## Acknowledgments

- Research compiled from official student program pages
- Verification information from SheerID, UNiDAYS, and Student Beans
- Icons using native emoji for universal compatibility

---

<p align="center">
  <strong>Made for students, by students</strong><br>
  <sub>Stop paying full price. Start accessing your benefits.</sub>
</p>
