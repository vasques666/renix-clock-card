# reNix Clock Card
<p align="center">
  <img src="docs/images/renix-clock-card.png" alt="Renix Clock Card" width="100%">
</p>
A custom Home Assistant Lovelace card with a layered reNix tube-style clock, weather/date information and configurable sensor panels.

## Version

**1.0.0 — stable release**

## Features

- Integrated `reNix-Regular.woff2` font.
- 24-hour clock with seconds and grid layers.
- Weather icon, date and weekday.
- Outside temperature/humidity, pressure and room temperature/humidity.
- Pressure displayed to one decimal place.
- Independent night brightness for upper and lower sections.
- Configurable clock glow and colors through the visual editor.
- Frosted Glass blur support.
- Theme-controlled card background, border, shadow and radius when set to `null`.

## Installation

### HACS

The easiest way to install Renix Clock Card is through HACS.

1. Open **HACS** in Home Assistant.
2. Go to **Frontend**.
3. Click the three-dot menu in the top-right corner.
4. Select **Custom repositories**.
5. Add:

   `https://github.com/vasques666/renix-clock-card`

6. Select **Dashboard** as the repository type.
7. Click **Add**.
8. Find **Renix Clock Card** and install it.
9. Restart Home Assistant or reload the Lovelace resources.

### Manual installation

Download `renix-clock-card.js` from the repository and add it as a Lovelace resource.

## Example

See [`example.yaml`](example.yaml).
