# Sierra Avalanche Center Dashboard
Authors: Thomas Bergamaschi, Josh Lowy, Kevin Scheller

## About
This is an avalanche danger analysis tool for the Tahoe Basin region.  Using cumulative data acquired from the Sierra Avalanche Center (non-profit updated by USDA forecasters) of avalanche reports, observations, and forecasts we built a dashboard for seasonal analysis of Tahoe avalanches.  The current tools in place for the public on the
[SAC website](https://www.sierraavalanchecenter.org/) give insight to local/specific dangers present, but provide no context for seasonal observation or weather correlation.  The charts we've built provide greater context to the conditions present throughout a winter season and allow for direct comparison to reported weather/precipitation.

## [Video Walkthrough](https://youtu.be/lHbNKe1klBw)

## Charts / Tools
- **Incident/Observation Map:**
  This map displays all reported observations and incidents of avalanches during the selected season.  The map is interactive and can be explored for specific areas or data.  Each map feature has a link back to the full observation/incident report.
 - **Stacked Precipitation Chart:**
  This chart is intended to correlate local precipitation and snowfall data with details from reported avalanche incidents and forecasts.  All charts are vertically aligned by date.  By following peaks and troughs of precipitation from the top portion downward, one can read into the changes/appearance of certain avalanche dangers and factors.

## Deployment
  Our cloud hosted database is password protected to avoid overdraw and limit requests, so this project is not available for local deployment, but can be viewed through the video walkthrough above.
