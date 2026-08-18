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

## HACS installation

1. Open HACS in Home Assistant.
2. Add this repository as a **Custom repository** with category **Dashboard**.
3. Install `reNix Clock Card`.
4. Add the resource if HACS does not do so automatically.
5. Add `type: custom:renix-clock-card` to a Lovelace dashboard.

## Example

See [`example.yaml`](example.yaml).
