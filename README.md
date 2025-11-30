# Xavier Cardona Ariza - Interactive Portfolio

A modern, interactive single-page portfolio showcasing professional experience, skills, and achievements as a Senior Software Engineer specializing in React, Node.js, and TypeScript.

## 🌟 Features

### Interactive Visualizations
- **Competency Matrix (Radar Chart)**: Visual representation of technical proficiencies across Frontend, Backend, Database/Data, DevOps/Infra, and AI/Innovation
- **Industry Domain Experience (Doughnut Chart)**: Distribution of professional experience across HealthTech and B2B SaaS/Services sectors

### Dynamic Timeline Navigation
- Click-to-explore interactive career timeline
- Detailed role views with project breakdowns
- Smooth transitions and hover effects
- Active state indicators for selected positions

### Responsive Design
- Mobile-first approach with Tailwind CSS
- Optimized layouts for all screen sizes
- Print-friendly styles for PDF generation

### Professional Content
- **Current Position**: Senior Software Engineer at Gartner
  - Capterra platform enhancements
  - Partner and Vendor Portal development
  - AI-powered Help Center integration
- **Previous Roles**: Fixbee, HealthOne NOVA (Cegedim), Dataflow API/UI (Cegedim/Stacks)
- **Technical Arsenal**: Comprehensive skills grid organized by Frontend, Backend & Data, and Infrastructure & Innovation

## 🎨 Design Philosophy

### Color Palette
The portfolio uses a carefully curated warm neutrals and professional blue theme:
- **Background**: `#F9FAFB` (Gray 50) - Warm neutral base
- **Primary Text**: `#1F2937` (Gray 800)
- **Accent**: `#3B82F6` (Blue 500) - Tech professional
- **Secondary Accent**: `#F59E0B` (Amber 500) - Highlights

### UX Principles
- **Progressive Disclosure**: Timeline-based navigation prevents information overload
- **Visual Hierarchy**: Charts provide high-level overview before detailed text
- **Interactivity**: Hover states, smooth transitions, and click interactions enhance engagement
- **Accessibility**: Semantic HTML, proper contrast ratios, and keyboard navigation support

## 🛠️ Technology Stack

- **HTML5**: Semantic markup with accessibility in mind
- **Tailwind CSS**: Utility-first styling via CDN
- **Chart.js**: Data visualization for skills and domain expertise
- **Font Awesome**: Icon library for visual enhancement
- **Vanilla JavaScript**: Dynamic content rendering and state management

## 📊 Data Structure

The portfolio is driven by a structured data model:

```javascript
cvData = {
  roles: [
    {
      id: "unique-identifier",
      company: "Company Name",
      title: "Job Title",
      period: "Date Range",
      location: "Location",
      summary: "Brief overview",
      projects: [...], // For roles with multiple projects
      bullets: [...],  // For roles with achievement lists
      tech: [...]      // Technology stack used
    }
  ]
}
```

## 🚀 Usage

### Viewing Locally
Simply open `index.html` in a modern web browser. No build process or dependencies required.

### Exporting as PDF
Click the "Save PDF" button in the header or use your browser's print function (Cmd/Ctrl + P) to generate a PDF version.

### Customization
To adapt this portfolio for your own use:

1. **Update Data**: Modify the `cvData` object in the `<script>` section (lines 252-357)
2. **Adjust Colors**: Update the Tailwind config (lines 23-36) and color palette comments (lines 14-20)
3. **Modify Charts**: Adjust chart data in the `renderCharts()` function (lines 373-428)
4. **Edit Content**: Update personal information in the intro section (lines 112-124)

## 📐 Key Sections

### 1. Header/Hero
- Immediate identity and contact information
- Sticky navigation with quick links
- PDF export functionality

### 2. Professional Profile
- Elevator pitch highlighting specializations
- Contact links (email, phone)
- Location information

### 3. Analytical Dashboard
- **Competency Matrix**: Visualizes full-stack capabilities
- **Domain Expertise**: Shows industry experience distribution
- Provides data-driven overview before detailed exploration

### 4. Interactive Timeline
- Chronological career history
- Click-to-select navigation
- Visual indicators for active role

### 5. Detail View
- Dynamic content injection based on timeline selection
- Special layouts for different role types
- Technology stack badges
- Project cards for multi-project roles
- Achievement lists for other positions

### 6. Technical Arsenal
- Organized skills grid
- Frontend, Backend & Data, Infrastructure & Innovation categories
- Visual indicators (colored dots) for skill grouping

### 7. Education Footer
- Academic background
- Degrees and institutions

## 🎯 Code Highlights

### State Management
- Simple state object tracks selected role
- Pure JavaScript without framework overhead

### Dynamic Rendering
- Timeline auto-generated from data
- Detail view re-renders on role selection
- Smooth opacity transitions for content changes

### Responsive Charts
- Configured for aspect ratio maintenance
- Mobile-optimized sizing
- Accessible color choices

## 📱 Browser Compatibility

Tested and optimized for:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📄 File Structure

```
portfolio/
├── index.html          # Main portfolio file (complete application)
└── README.md          # This file
```

## 💡 Design Decisions

### Why Single File?
- **Portability**: Easy to share and deploy
- **Simplicity**: No build process required
- **Performance**: Minimal HTTP requests
- **Maintainability**: All code in one place for small projects

### Why Chart.js?
- Lightweight and reliable
- Good documentation
- Responsive by default
- Wide browser support

### Why Tailwind CDN?
- Rapid development
- No build configuration
- Consistent utility classes
- Easy customization via config

## 📧 Contact

**Xavier Cardona Ariza**
- Email: xcariza@gmail.com
- Phone: +34 669 606 262
- Location: Sant Cugat del Vallès, Barcelona

## 🔄 Version History

- **Current**: Interactive portfolio with dual-chart dashboard and timeline-based navigation
- Features comprehensive project breakdowns for current position
- Optimized for both web viewing and PDF export

## 📝 License

This portfolio template is personal work. Feel free to use the structure and code as inspiration for your own portfolio, but please respect the personal content and information.

---

*Generated from Xavier Cardona Ariza's updated CV data.*
