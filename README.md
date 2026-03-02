# Uruguay EV Chargers Monitor

A web-based frontend for monitoring electric vehicle (EV) charging stations across Uruguay. This application provides real-time visibility into charger status, historical analytics, and predictive insights to help EV drivers find available chargers and plan trips with confidence.

**Backend:** [uruguay-ev-chargers-monitor-backbone](https://github.com/alexisml/uruguay-ev-chargers-monitor-backbone)

## Features

### Charger Network Tracking
- **New charger alerts** — get notified when new charging stations are added to the network
- **Removed charger alerts** — get notified when charging stations are removed or decommissioned
- **Live status map** — view the current status of all chargers on an interactive map

### Predicted Availability
- **Availability forecasts** — see expected charger availability at a given location, time, and day of the week, based on historical usage data
- **Peak usage indicators** — identify high-demand periods to plan charging sessions at off-peak times

### Problematic Charger Detection
- **Frequently unavailable chargers** — flag chargers that go offline repeatedly
- **Permanently occupied chargers** — detect chargers that appear to be always in use, suggesting possible abuse or malfunction
- **Error-state chargers** — surface chargers that report error states or inconsistent data

## MVP Plan

### Phase 1 — Foundation
- [ ] Set up the frontend project (framework, build tooling, linting)
- [ ] Integrate with the backbone API for charger data
- [ ] Display a list/map of all known chargers with current status

### Phase 2 — Charger Network Changes
- [ ] Show newly added chargers (highlighted on map and in a dedicated feed)
- [ ] Show recently removed chargers
- [ ] Basic notification/alert UI for network changes

### Phase 3 — Predicted Availability
- [ ] Fetch and display historical availability data per charger
- [ ] Present predicted availability by day of week and time of day
- [ ] Add visual indicators (e.g. heatmap or chart) for peak vs. off-peak periods

### Phase 4 — Problematic Charger Detection
- [ ] Display chargers flagged as frequently unavailable
- [ ] Display chargers flagged as always in use
- [ ] Display chargers flagged for error states or anomalies
- [ ] Aggregate a "health score" view for each charger

### Phase 5 — Polish & Release
- [ ] Responsive design for mobile use
- [ ] User preferences (favorite chargers, notification settings)
- [ ] Performance optimization and caching

## License

This project is licensed under the Apache License 2.0 — see the [LICENSE](LICENSE) file for details.
