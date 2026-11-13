# Long Horizon Observatory

Long Horizon Observatory supports scientists with use-inspired research, bringing precision-simulation
infrastructure and agentic-AI tools into scientific contexts to accelerate research and streamline
operations.

We prepare data for high-resolution coastal simulation: we acquire, reconcile and quality-check
boundary forcing and bathymetry from public sources, and build open-source tools to serve and
visualize the ocean and atmosphere. With research collaborators, we are building toward sub-100 meter
simulation of inshore waters and real-time 3D views of the results.

## Data for coastal models

- **[topobathykit](https://github.com/lhzn-io/topobathykit)**: policy-driven topobathymetric fusion.
  Seamless grids from survey, lidar and crowdsourced soundings, with vertical datum transformation
  and per-pixel provenance. [Docs](https://topobathykit.docs.lhzn.io)
- **[forcingkit](https://github.com/lhzn-io/forcingkit)**: spatiotemporal forcing for Earth-system
  models. Selects, regrids and serves model-ready time series with provenance from regional ocean
  forecasts (NYOFS, NECOFS, DBOFS, HYCOM) and the HRRR atmosphere. [Docs](https://forcingkit.docs.lhzn.io)
- **[insitukit](https://github.com/lhzn-io/insitukit)**: in situ ocean observations, fetched and
  summarized. NOAA CO-OPS and ERDDAP clients, record statistics and a compact JSON time-series format.

## Viewing ocean data

- **[vantagekit](https://github.com/lhzn-io/vantagekit)**: shared camera navigation for terrain,
  ocean and vessel viewers. Orbit and fly modes in real units, gamepad and touch input, and view
  links, for three.js, MapLibre GL JS and Omniverse Kit. [Live demo](https://lhzn-io.github.io/vantagekit/demo/)
- **[lhzn-blue](https://github.com/lhzn-io/lhzn-blue)**: the source of
  [longhorizon.blue](https://longhorizon.blue), live buoy and shore-station readings for Long Island
  Sound beside the forecasts and earlier years. In alpha; not for navigation.
- **[csb-census](https://github.com/lhzn-io/csb-census)**: an open, reproducible census of the
  crowdsourced bathymetry published by the IHO DCDB: unique soundings, duplicates and coverage per
  provider.

## In the field and at the edge

- **[biologger-sim](https://github.com/lhzn-io/biologger-sim)**: streaming inertial navigation and
  behavior classification for animal-borne tags, with 3D replay, built with the
  [WHOI Marine Predators Group](https://marinepredators.whoi.edu/).
- **[labtender](https://github.com/lhzn-io/labtender)**: a lab board and GPU claim ledger for mixed
  fleets of workstations, Jetsons, Macs and cloud GPUs, shared by people and AI agents.
- **[uplift](https://github.com/lhzn-io/uplift)**: instrumentation and causal measurement for AI
  agents in small organizations.

Long Horizon Observatory is a self-funded research lab on Long Island Sound. Issues and pull requests
are welcome on all of the public repositories.

## More

- [longhorizon.eco](https://longhorizon.eco): our work and Field Notes
- [Engineering blog](https://lhzn-io.github.io)
- [longhorizon.blue](https://longhorizon.blue): marine conditions, one waterway at a time

*Science Endures.*
