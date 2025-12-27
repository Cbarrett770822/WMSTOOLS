# WMS Tools Suite - Launch Pad

A professional landing page for accessing the complete suite of Warehouse Management System (WMS) tools.

## 🚀 Included Applications

### 1. **WMS Discovery**
- **URL**: https://wmsdiscovery.netlify.app/login
- **Purpose**: Interactive questionnaire tool for warehouse operations assessment
- **Features**:
  - Multi-stage questionnaires
  - Company & warehouse profiles
  - Pain point analysis
  - User management with role-based access

### 2. **WMS ROI Assessment**
- **URL**: https://wmsroi.netlify.app/login.html
- **Purpose**: Calculate ROI for WMS implementations
- **Features**:
  - Detailed ROI calculations
  - Cost-benefit analysis
  - Implementation roadmap planning
  - Industry benchmark comparisons

### 3. **Demo Assist**
- **URL**: https://demoassist.netlify.app/
- **Purpose**: AI-powered data generator for WMS demos
- **Features**:
  - AI-generated realistic test data
  - Storer & SKU creation
  - ASN (Advance Ship Notice) generation
  - Shipment order creation

### 4. **WMS Demo Dashboard**
- **URL**: https://wmsdemodashboard.netlify.app/
- **Purpose**: Generate professional presales dashboards
- **Features**:
  - Custom dashboard creation
  - Real-time metrics visualization
  - Client presentation tools
  - Data visualization components

### 5. **User Admin**
- **URL**: https://wmsadminuser.netlify.app/
- **Purpose**: Centralized user management for all WMS applications
- **Features**:
  - User account management
  - Role-based access control
  - App-specific permissions
  - Centralized authentication system

## 🎨 Design Features

- **Modern Dark Theme**: Professional dark mode interface with gradient accents
- **Responsive Design**: Fully responsive layout that works on all devices
- **Smooth Animations**: Card hover effects and entrance animations
- **Category Organization**: Tools organized by Assessment, Financial, Demo, Presales, and Admin categories
- **Icon System**: Custom SVG icons for each tool
- **Accessibility**: Semantic HTML and proper contrast ratios

## 🛠️ Technology Stack

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with CSS Grid and Flexbox
- **Vanilla JavaScript**: Lightweight interactions and animations
- **Google Fonts**: Inter font family for clean typography

## 📦 Deployment

### Deploy to Netlify

1. Push this repository to GitHub
2. Connect to Netlify
3. Deploy settings:
   - **Build command**: None (static site)
   - **Publish directory**: `.` (root)

### Manual Deployment

Simply upload all files to any static hosting service:
- index.html
- styles.css
- script.js
- netlify.toml (for Netlify-specific configuration)

## 🎯 Usage

1. Open the landing page in a browser
2. Browse the available WMS tools
3. Click "Launch Tool" on any card to open the application in a new tab
4. Each tool has its own authentication and features

## 🔧 Customization

### Adding New Tools

Edit `index.html` and add a new card in the `.tools-grid` section:

```html
<div class="tool-card" data-category="your-category">
    <div class="card-header">
        <div class="icon-wrapper your-color">
            <!-- Your SVG icon -->
        </div>
        <span class="badge">Your Badge</span>
    </div>
    <h2>Tool Name</h2>
    <p class="description">Tool description</p>
    <ul class="features">
        <li>Feature 1</li>
        <li>Feature 2</li>
    </ul>
    <a href="your-url" class="btn" target="_blank">
        Launch Tool
        <svg><!-- Arrow icon --></svg>
    </a>
</div>
```

### Changing Colors

Edit CSS variables in `styles.css`:

```css
:root {
    --primary-gradient: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    --discovery-color: #10b981;
    --roi-color: #f59e0b;
    --demo-color: #3b82f6;
    --dashboard-color: #8b5cf6;
    --admin-color: #ec4899;
}
```

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📄 License

All rights reserved © 2024 WMS Tools Suite

## 🤝 Support

For support with individual tools, please refer to their respective documentation.
