# Uruguay EV Chargers Monitor

A web-based frontend for monitoring electric vehicle (EV) charging stations across Uruguay. This application provides historical analytics and predictive insights to help EV drivers plan charging sessions with confidence. For real-time charger status, use the UTE app directly.

**Backend:** [uruguay-ev-chargers-monitor-backbone](https://github.com/alexisml/uruguay-ev-chargers-monitor-backbone)

## Features

### Charger Network Tracking
- **New charger alerts** — get notified when new charging stations are added to the network
- **Removed charger alerts** — get notified when charging stations are removed or decommissioned

### Predicted Availability
- **Availability forecasts** — see expected charger availability at a given location, time, and day of the week, based on historical usage data
- **Peak usage indicators** — identify high-demand periods to plan charging sessions at off-peak times

### Problematic Charger Detection
- **Frequently unavailable chargers** — flag chargers that go offline repeatedly
- **Permanently occupied chargers** — detect chargers that appear to be always in use, suggesting possible abuse or malfunction
- **Error-state chargers** — surface chargers that report error states or inconsistent data

## MVP Plan

See [docs/MVP_PLAN.md](docs/MVP_PLAN.md) for the full phased roadmap.

## License

This project is licensed under the Apache License 2.0 — see the [LICENSE](LICENSE) file for details.
