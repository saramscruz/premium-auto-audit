# GA4 Proxy Baseline — Shared Methodology

## What this dataset is

Source: Google BigQuery public dataset — Google Merchandise Store GA4 export  
Sessions: 344,640  
Period: Standard public sample period  

This is a high-consideration e-commerce funnel from a real GA4 implementation.

## What it establishes

Three structural patterns that apply to high-consideration digital purchase funnels broadly:

1. **Drop-off concentration** — the largest single session drop occurs between product view and the first commitment action (add-to-cart equivalent). This is the funnel's structural weak point.
2. **Return visitor lift** — return visitors convert at a materially higher rate than first-visit sessions. The proxy shows a 51.5x lift. The absolute figure is not claimed for any brand; the pattern is.
3. **Channel x device interaction** — the mobile conversion gap is channel-specific, not device-specific. Mobile organic underperforms desktop organic more than mobile paid underperforms desktop paid. The bottleneck is upstream content, not the funnel itself.

## What it is not

- Automotive data
- Portuguese market data
- Any brand's actual performance

The 1.41% conversion rate, the 51.5x return visitor lift, and the channel splits are structural patterns only. They establish the analytical framework. All brand-specific quantitative claims derive from direct configurator observation and Google Trends PT.

## Constraint — enforced throughout

No brand-specific conclusion may be stated as if it derives from this dataset.  
The proxy establishes the pattern. Direct observation and search data establish the brand-specific finding.

## Where this appears in the final document

Once, in the methodology section. It is not repeated per brand. Brand sections do not cite these figures as their own.

## Google Trends — methodology note
Source: Google Trends PT · Web Search · Past 12 months · observed at stated dates.

Trends indices are relative, not absolute. Each value (0–100) represents search interest
relative to the highest point in the selected time window for that query. This means:

- The same query observed on a different date will return a different index value.
- Indices cannot be compared across different queries or brands as absolute measurements.
- BREAKOUT status (>5000% increase) and percentage rises in rising/top queries are
  directional signals, not precise figures.

All index values in this audit are stated with their observation date and time window.
They are used to establish relative demand tiers and directional trends only.
No brand-specific claim is made that depends on an index value being stable or precise.
