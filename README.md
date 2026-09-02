# Glacier's Edge Council Command Center v12.3

Operations-dashboard redesign based on the approved dark command-center reference.

## Overview redesign
- Four prominent KPI cards
- Unit Health by District scorecard with red/yellow/green counts and health-score rings
- Five Unit Metrics progress bars
- Dedicated Priority Indicators panel
- Membership, Safeguarding Youth, and Charter Renewal donut/status panels
- District navigation buttons plus District and Unit dropdown drill-down
- Council → District → Unit scope continues to drive every dashboard

## Data workflow
Admin loads the five Scouting America CSV exports locally in the browser. Unit Metrics and Charter Renewal define active units. Generate `data.js` from Admin for a sanitized public Viewer.

Do not publish raw CSVs or the Admin folder to a public repository.


## v12.4 — Direct dashboard drill-down
Navigation is no longer limited to the left sidebar.
- Click a district in Unit Health by District to scope the entire dashboard to that district.
- Click any unit in the Overview or detail tables to scope directly to that unit.
- Overview unit rows open the 360° Unit Profile.
- Click top KPI cards, Five Unit Metrics rows, Priority Indicators, and status-panel links to open their detailed dashboard.
- Keyboard Enter/Space is supported for clickable dashboard elements.


## v12.5 Metric exception drill-down

On the Unit Metrics dashboard, each of the five metric cards is now clickable. Selecting a metric filters the unit table to only units **not meeting** that metric within the current Council/District/Unit scope. Click the selected metric again, or use **Show all units**, to clear the filter. The same exception filter is applied when drilling into a metric directly from the Overview performance bars.
