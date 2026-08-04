# Project brief

## Description

Open Sans version of the Melbourne 3840×804 split-flap clock with live-time entrance animation and mobile preview scaling.

## Build brief

Purpose:
Create a separate Open Sans variant of creative-innovation-labs-bmc/Melbl8-Clock03-Split-flap without changing the existing live repository.

Reference build:
Use the existing live-launch test behaviour from creative-innovation-labs-bmc/Melbl8-Clock03-Split-flap/live-launch.html and clock-live-launch.js.

Main requirements:
- Fixed production canvas: 3840 × 804.
- Use Open Sans from Google Fonts for all letters and numbers.
- Retune font sizes, offsets, spacing and letter spacing so MEL, weekday, HH:MM:SS and the full stage fit cleanly without clipping.
- Keep the existing flap styling, colours and animation treatment.
- During the entrance animation, already-active clock digits must continue tracking live time.
- Unchanged HH/MM/SS digits must not flap unnecessarily.
- Include portrait-aware and landscape-aware mobile auto-scaling for testing.
- Lightweight vanilla HTML, CSS and JavaScript compatible with NVIDIA Shield signage playback.
- Include noindex/nofollow/noarchive metadata, robots.txt and .nojekyll.
- Enable GitHub Pages from main/root.
- Preserve Melbourne timezone and MEL location defaults.

Constraints:
Do not modify the source repository. Do not use WebGL or processor-heavy frameworks.
