# DevPulse — Cloud Infrastructure SaaS Landing Page

DevPulse is a high-performance, responsive landing page for a cloud observability and automated remediation SaaS platform. Built using semantic HTML5 and custom CSS3 with custom properties (CSS variables), it provides a modern UI featuring real-time feature highlights, interactive tier pricing, and a workload configuration estimator form.

---

## 🚀 Features

- **Semantic HTML5 Layout:** Structured with accessibility standards in mind (`<header>`, `<main>`, `<section>`, `<article>`, `<nav>`, `<footer>`).
- **Custom CSS Architecture:** Built using native CSS variables for color themes, typography, and fluid spacing.
- **Hero Section:** Features release badges, compelling value propositions, and primary calls-to-action (CTAs).
- **Feature Matrix:** Highlights core infrastructure capabilities (Latency Tracking, Log Aggregation, Auto-Remediation).
- **Pricing Tiers:** Clean, visual pricing grid supporting tiered subscriptions (*Developer*, *Pro Cluster*, and *Enterprise Dedicated*).
- **Workload Estimator Form:** Included interactive lead generation form allowing potential users to input node counts and daily log volumes to calculate recommended deployment blueprints.

---

## 🛠️ Project Structure

```text
.
├── index.html   # Main HTML document structure
├── style.css    # Custom CSS stylesheet using CSS variables & Grid/Flexbox
└── README.md    # Project overview and documentation
```

---

## 📋 File Breakdown

### `index.html`
- **Navigation Header:** Sticky top bar with brand identity and deep links to key page sections.
- **Hero Section (`#hero`):** Displays product announcements and primary conversion buttons.
- **Features Section (`#features`):** Grid layout presenting key platform highlights.
- **Pricing Section (`#pricing`):** Cards detailing plans with highlighted visual weight for popular choices.
- **Workload Registration (`#register`):** Form interface accepting user emails, node capacities, log volumes, and tier preferences.
- **Footer Section:** Copyright notices and quick navigation links.

### `style.css`
- **Root Variables:** Centralized theme variables (`--primary`, `--bg-light`, `--text-main`, etc.) for consistent design maintenance.
- **Reset & Base Styles:** Global box-sizing, custom scroll behavior, and baseline font rules.
- **Component Styling:**
  - `.btn`: Standardized button layouts with focus states and hover transitions.
  - `.feature-grid` & `.pricing-grid`: CSS Grid implementation for adaptive layouts.
  - `.pricing-card.featured`: Visual elevation effects for conversion optimization.

---

## 🚦 Getting Started

1. **Clone or Download:** Save both `index.html` and `style.css` into the same directory.
2. **File Alignment:** Ensure your stylesheet reference inside `index.html` matches the file name:
   ```html
   <link rel="stylesheet" href="style.css"/>
   ```
3. **Open in Browser:** Double-click `index.html` or run a local server (e.g., via VS Code Live Server) to view the site.

---

## 🔧 Future Enhancements & TODOs

- Add vector SVG icons inside the `.feature-icon` containers.
- Implement JavaScript logic to make the Workload Estimator dynamic (calculating costs live based on input values).
- Add full responsive media queries (`@media`) for mobile navigation toggling.