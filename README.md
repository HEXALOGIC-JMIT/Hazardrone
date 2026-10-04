# HAZARDRONE – Hardware, Sensing and Analytics Design

Interactive dashboard and 3D visualization suite for HAZARDRONE: aerial infrastructure inspection, sensor telemetry, and hazard diagnostics.

## Features
- Interactive 3D Drone & Payload Digital Twin
- Substation & Corridor Telemetry Mapping
- Multi-Sensor Fusion Diagnostics (LiDAR, Radiometric Thermal, Gas/CH₄, Ultrasonic)
- Automated Defect & Severity Pinpointing (CUSUM, Point Deviation, Delta-T)
- Engineer Review & Inspection Report Generation

## Deployment to Vercel

This repository is optimized for one-click static deployment to [Vercel](https://vercel.com):

1. Go to [vercel.com/new](https://vercel.com/new).
2. Connect your GitHub account and import `HEXALOGIC-JMIT/Hazardrone`.
3. Keep default settings (Framework Preset: **Other** / Static).
4. Click **Deploy**.

Entrypoint: [`index.html`](index.html) configured via [`vercel.json`](vercel.json).
