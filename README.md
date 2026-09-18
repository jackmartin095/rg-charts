# RG Charts

Interactive Chart.js visualizations built for FanGraphs RotoGraphs pieces. Each file is a standalone HTML chart embedded in a published article.

A note on versioning: many pieces have multiple numbered files (`_v2`, `_v3`, `_v6`, etc.), kept from the development process. Within each group below, the highest version number or most recently dated file is the one actually used in the published piece; earlier versions are kept for reference only.

## Rookie pitcher composite series
Weighted composite Z-score ranking a 2026 rookie pitcher class across K-BB%, Stuff+, CSW%, Z-Contact%, and HardHit%, then tiered and broken down by group.
- `rookie_composite_no_avg_labels.html`
- `rookie_radar_tier1.html`
- `rookie_radar_tier2.html`
- `rookie_radar_tier2_1.html`

## BABIP / xwOBA regression series
Tracking hitters' BABIP against xwOBA to identify regression candidates, with a follow-up piece isolating the power component.
- `babip_xwoba_scatter_v3.html`
- `babip_xwoba_scatter_v6.html`
- `babip_xwoba_scatter_v7.html`
- `babip_xwoba_scatter_v9.html`
- `babip_xwoba_part2_rounds_v3.html`
- `babip_xwoba_part2_power_v4.html`
- `babip_xwoba_part2_power_v5.html`

## Z-O normalization
Tracking each hitter's 2026 Z-O gap (zone swing rate minus chase rate) against their own 2024-2025 baseline, testing how much a first-half discipline swing actually holds through the second half.
- `zo-volcano-2026.html`

## Bat speed and young hitters
Layering bat speed against squared-up contact rate and chase rate for hitters under 25, to test how much raw bat speed predicts success.
- `u25_batspeed_labeled.html`
- `u25_batspeed_labeled_v2.html`
- `u25_batspeed_squaredup_v2.html`

## Stuff+ vs Location+
Comparing Stuff+ and Location+ across 2026 starters to show stuff correlates more strongly with run prevention than command does.
- `rg_stuff_location_gap_v2.html`

## Tracking Four-Seam Velocity
- `velo_chart.html` (four-seam velocity risers/fallers)

## Stance Shifters
- `tinkerer_scatter.html` (batting stance tinkerers)

## Times Through the Order Piece
- `tto-drops-v3.html`
- `tto-pickups-v2.html`
(times through the order)

## IVB Reliers
- `ivb-reliance-scatter-v6.html` (fastball IVB)

## Home/Away Splits
- `rg_homeaway_scatter_v1.html`
- `rg_diverging_homeaway_v1.html`
(home/away splits)

## Power Sweeper
- `rg_power_sweeper_v1.html`
- `rg_power_sweeper_thr_v1.html`

## OOPSY Projections vs xwOBA
- `oopsy_woba_chart.html`
- `oopsy_woba_chart_3.html`
- `rg_woba_xwoba_v1.html`
- `xwoba-scatter-v6.html`

## Handedness Splits
- `team_wrc_lhp_vs_rhp_y72_2026.html`

## Tools / utilities
- `rg_schedule_tracker.html`
- `august_ticker.html`

## Dev / test
- `weighted_scatter_test_3.html`
- `fangraphs-leaderboards (9).csv` (source data export)

## Author
Jack Martin, baseball columnist at FanGraphs RotoGraphs. jackmartin095@gmail.com
