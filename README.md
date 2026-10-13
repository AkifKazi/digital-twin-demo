# Digital Twin — live demo

**Open it:** <https://akifkazi.github.io/digital-twin-demo/>

The WebGL build of a Unity digital twin of an industrial feeder (hopper, separator, conveyor):
live or simulated sensor readings on cards joined to the machine by leader lines, warning and
critical alarms, a service schedule, cross-section and X-ray views, an Ask assistant, and layouts
for desktops and phones. Readings, limits and the process model are demonstration values.

This repository holds only the built files that GitHub Pages serves. The Unity project, its
documentation and how to rebuild this site are in
[digital-twin-project](https://github.com/AkifKazi/digital-twin-project).

## Using it

- Drag to orbit, scroll or pinch to zoom. FULL BODY, CROSS SECTION and X-RAY change the view.
- Click a card to see its history; TELEMETRY / SERVICE switches to the service schedule.
- ASK opens the assistant; the gear opens viewer settings (scale, contrast, card rails, camera).
- Add `?lang=<code>` to the address to pick a language from the build's text table.

## Updating

Build the Unity project with its Web build profile, copy `index.html`, `Build`, `TemplateData` and
`StreamingAssets` over this repository's root, and push. Pages publishes `main` at the root.
