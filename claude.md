# Maple Street Community Garden Tracker

Single HTML file app. State stored in localStorage key `gtv3`.
SVG map with viewBox="0 0 100 100". Zones stored as % coordinate points.
Key functions: renderZones(), renderItems(), renderLogs(), applyTransform()
Key state: S (app state), isAdmin, selZone, selItem, mapZoom, panX, panY
Fonts: DM Serif Display (headings/labels), DM Sans (body)
Colours: --g800 green, --a800 amber, --r700 red, --n500 grey
Zone colours stored as S.zones[i].color (string e.g. 'red','blue','gray').
Polygon close detection: click within (5/zoom) units of first point to close.
All copy must be American English.
heic2any library available at https://cdn.jsdelivr.net/npm/heic2any@0.0.4/dist/heic2any.min.js