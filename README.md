# MyCitiBike NYC Station Status Map

Built an interactive Leaflet.js map that visualizes real-time status of over 1,000 Citi Bike stations across New York City. Categorized stations based on number of available bikes using live API data and rendered custom markers to show availability at a glance.

## Tools & Technologies Used

- JavaScript
- Leaflet.js
- HTML/CSS
- d3.js
- Live JSON APIs (Citi Bike GBFS feeds)

## File Structure

```text
.
├── index.html              # Landing page for map
├── static/
│   ├── js/logic.js         # JavaScript mapping logic
│   ├── css/style.css       # Custom map styles
│   └── img/                # Custom marker images
```

## Skills Demonstrated

- Consuming and transforming real-time API data
- Categorizing data based on conditional logic
- Building dynamic map visualizations using Leaflet.js
- Using custom marker styles to improve UX
- Organizing modular front-end code for clarity

## Key Findings

- Visualized over 1,000 Citi Bike stations by status in real time.
- Defined availability tiers:
  - **Empty**: 0 bikes  
  - **Low**: 1–4 bikes  
  - **Normal**: 5+ bikes  
- Integrated two live API endpoints (station info + status) to enrich each marker.
- Enabled users to identify low-stock and out-of-service stations at a glance.
