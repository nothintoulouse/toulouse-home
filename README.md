# toulouse.cloud

Personal digital hub for Brayden Toulouse.

## Overview

Central landing page linking to all toulouse.cloud subdomains and projects.

## Live Subdomains

- **resume.toulouse.cloud** - Professional resume
- **pages.toulouse.cloud** - Personal tools and apps
  - /dashboard-widget/ - Calendar and to-do list

## Planned Subdomains

- **cal.toulouse.cloud** - Personal calendar/scheduling
- **media.toulouse.cloud** - Media server access

## Tech Stack

- Pure HTML/CSS (no frameworks)
- Scalable card-based design
- Mobile-responsive
- Fast loading
- Hosted on GitHub Pages

## Design Principles

- Clean, professional aesthetic
- Texas A&M branding (maroon and navy)
- Easy to add new cards
- Accessible and semantic HTML
- Print-friendly

## Adding New Cards

To add a new subdomain card, copy this template in the cards-grid section:

```html
<a href="https://your-subdomain.toulouse.cloud" class="card">
    <span class="status-badge status-live">Live</span>
    <!-- OR -->
    <span class="status-badge status-soon">Coming Soon</span>
    
    <svg class="card-icon" fill="none" stroke="currentColor" viewBox="0 0 24 24">
        <!-- Your icon SVG path here -->
    </svg>
    <h2 class="card-title">Your Title</h2>
    <p class="card-description">Description of your subdomain.</p>
    <span class="card-url">
        your-subdomain.toulouse.cloud
        <svg fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"/>
        </svg>
    </span>
</a>
```

## License

Personal site - all rights reserved.
