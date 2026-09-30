# HRV Readiness & Daily Stress Check
Daily log form: resting HR (bpm), subjective energy (1-5), sleep hours, stress level (1-5). Calculate composite readiness score (0-100). Color-coded: green ≥70, yellow 40-69, red <40. 7-day trend chart using canvas. localStorage history.

## Features
- Daily check-in form: resting HR, sleep hours, energy level (1-5), stress level (1-5)
- Composite readiness score (0-100) using weighted formula: HR 25%, Sleep 30%, Energy 25%, Stress 20%
- Color-coded score display: green ≥70 (High), yellow 40-69 (Moderate), red <40 (Low)
- Score detail card with all component values
- 7-day trend chart using canvas with color-coded data points
- Green/yellow threshold lines on chart at 40 and 70
- History list showing last 7 entries with color-coded labels
- Duplicate date handling: today's entry replaces previous
- localStorage persistence with full history
- Responsive canvas with device pixel ratio support
- Button-group pickers for 1-5 ratings with aria-pressed state
