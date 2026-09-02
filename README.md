# Glacier's Edge Council Command Center v12.9.1

Council-wide feature-parity build based on Northern Lights v12.8.

## Scope
- Entire Glacier's Edge Council
- Driftless 08
- Northern Lights 07
- Rock River 09
- Individual unit drill-down within each district

## Features
- Dark command-center dashboard
- Direct Council → District → Unit drill-down
- Clickable KPI filters across Unit Metrics, Membership, Training, SYT, and Charter Renewal
- Five Unit Metrics exception filters show only units not meeting the selected metric
- Sortable columns across all unit tables; click a header to toggle ascending/descending
- Data-aware sorting for numbers, dates, health, Yes/No, SYT status, and unit names
- Priority Indicators and 360° Unit Profile
- Unique registered-adult headline count deduplicated by Member ID in Admin and safely pre-aggregated for Viewer
- Sanitized Viewer publishing with no names, Member IDs, emails, phones, addresses, or commissioner names

## Publishing
Open `admin/index.html`, load the five council reports, then generate Viewer `data.js`. Replace `viewer/data.js` with the generated file and publish only the `viewer` folder.


## v12.9.1 KPI + Sorting Fix

KPI filter cards now use persistent delegated click handling in both Admin and Viewer. This keeps KPI filtering active after table sorting, filtering, scope changes, and dashboard re-renders. Sortable headers, metric exception filters, direct unit drill-down, and Council → District → Unit scope behavior remain intact.
