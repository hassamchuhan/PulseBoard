# PulseBoard — Business Intelligence & Operations Dashboard

PulseBoard is a responsive, multi-page dashboard interface designed to bring common business metrics, customer insights, order operations, reports, and workspace preferences together in one clean workspace.

This project is a **front-end portfolio and learning project** built with HTML and Tailwind CSS. Its main objective is to practise and demonstrate semantic HTML, responsive layouts, reusable interface patterns, dashboard information hierarchy, data presentation, and accessible UI fundamentals before adding JavaScript or backend functionality.

> **Important demo notice:** The metrics, charts, customer records, orders, activity logs, report statistics, and other dashboard values are illustrative sample data. They are not verified business results and are not connected to a live company, database, analytics service, or API.

## Project Preview

PulseBoard uses a light, professional dashboard style with:
- A consistent sidebar and top navigation across pages
- Metric cards for at-a-glance summaries
- Tables, progress bars, timelines, and SVG-based chart visuals
- A restrained blue, emerald, amber, and neutral colour palette
- Responsive layouts intended to adapt to mobile, tablet, laptop, and desktop screens

## Main Objectives

- Build a realistic business dashboard interface using **HTML5 and Tailwind CSS**.
- Practise responsive design with utility classes and mobile-first layout adjustments.
- Organise business information into clear sections that are easy to scan.
- Create consistent navigation and visual patterns across multiple pages.
- Present sample business metrics through cards, tables, progress indicators, and inline SVG visuals.
- Strengthen front-end development skills as part of a broader full-stack learning journey.

## Pages and Features

| File | Purpose |
| --- | --- |
| `index.html` | **Overview:** high-level business metrics, performance visuals, recent activity, and top-product summaries. |
| `analytics.html` | **Analytics:** revenue and traffic visualisations, customer growth, and regional performance summaries. |
| `customers.html` | **Customers:** customer table, acquisition visualisation, and customer segment summaries. |
| `operations.html` | **Operations:** order processing metrics, order status distribution, fulfilment performance, recent orders, activity, and inventory summaries. |
| `reports.html` | **Reports:** report generation metrics, trend visuals, category breakdowns, popular reports, report health, and scheduled-report summaries. |
| `settings.html` | **Settings:** profile information, workspace preferences, notification preferences, security/access information, and recent account activity. |

The `assets/` directory is reserved for project assets such as images and other static resources.

## Technology Stack

- **HTML5** — page structure and semantic content
- **Tailwind CSS** — utility-first styling, layout, spacing, typography, colours, borders, and responsive behaviour
- **Inline SVG** — lightweight icons and static chart illustrations
- **Google Fonts (Inter)** — interface typography

Tailwind CSS is loaded using its CDN in the HTML pages. This keeps the learning project simple to run without a build process. For a production application, a configured Tailwind build and a reviewed deployment setup would be more appropriate.

## Responsive Design

The interface is designed to adapt to different viewport sizes, including:
- Small mobile screens (around 320–390px)
- Larger mobile screens (around 414px)
- Tablets (around 768px)
- Small laptops (around 1024px)
- Desktop and wide displays (1280–1920px)

Responsive behaviour includes layout changes, a desktop sidebar that is hidden on smaller screens, stacked cards, and horizontally scrollable data tables where needed. Actual rendering can vary by browser and device, so the pages should be tested at these widths before release.

## Demo Data and Functionality Limitations

PulseBoard currently demonstrates the **visual front end**, not a complete working business intelligence product.

### Why buttons and links may not work

- **Visual-only buttons:** actions such as exporting reports, creating reports, saving settings, cancelling edits, searching, filtering, and other controls may be included to show the intended interface. Unless a specific control has been connected to code, clicking it will not perform a real action.
- **No JavaScript behaviour:** this learning version is built without JavaScript. Therefore, interactive behaviours such as live search, filtering, sorting, pagination, dropdown logic, form validation, toggles that persist, and dynamic chart updates are not implemented.
- **No backend or database:** profile details, customer records, order statuses, inventory, report schedules, and settings are not loaded from or saved to a server or database.
- **No external service/API integration:** the dashboard is not connected to a real analytics provider, payment service, CRM, order-management system, authentication service, or reporting platform.
- **Navigation links:** links between the six pages should work when the corresponding relative file paths are present and correct. Links to features, sections, or pages that have not been implemented may be placeholders and may not navigate anywhere.
- **Static charts and indicators:** chart shapes, progress bars, and percentages are illustrative HTML/SVG visuals. They do not update from live or verified data.
- **Settings and security panels:** these panels are UI demonstrations only. They do not change account settings, manage real permissions, or provide actual authentication or security controls.

These limitations are intentional for the current stage of the project: the focus is on front-end layout and responsive UI practice. They should not be interpreted as evidence that a real business system is connected or operational.

## How to Run Locally

1. Download or clone this repository.
2. Open the `PulseBoard` project folder.
3. Open `index.html` in a modern web browser.

No package installation or build command is required for the current CDN-based version. An internet connection is required for the Tailwind CSS CDN and Google Fonts to load. You can also use the **Live Server** extension in Visual Studio Code for local development.

## Project Structure

```text
PulseBoard/
├── assets/
├── index.html
├── analytics.html
├── customers.html
├── operations.html
├── reports.html
├── settings.html
└── README.md
```

## Learning Outcomes

This project provides practice with:
- Semantic HTML structure and page organisation
- Tailwind CSS utility classes
- CSS Grid and Flexbox through Tailwind utilities
- Responsive design and breakpoint-based layouts
- Repeated navigation and dashboard UI patterns
- Tables, cards, progress indicators, and SVG visuals
- Clear presentation of business-style information
- Communicating the difference between a static prototype and a functional application

## Possible Future Improvements

The following are potential next steps, not features currently promised by this version:
- Add JavaScript for functional search, filters, sorting, pagination, and interactive controls.
- Connect forms and settings to persistent storage or a backend.
- Replace sample values with verified data from a documented API or database.
- Make charts data-driven and interactive.
- Add authentication and role-based access controls if the project evolves into a real application.
- Configure Tailwind CSS with a production build process and add automated accessibility and responsive tests.

## Status

**Front-end prototype / learning project.** The interface and sample data are intended for demonstration and portfolio use. The project is not a production-ready analytics platform.

---

Made as part of an ongoing front-end and full-stack development learning journey.
