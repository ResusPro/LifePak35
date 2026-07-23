# OBVS v0.1.2

A browser-only patient monitor simulator for educational use.

## Included

- LIFEPAK 35-inspired monitor layout
- Animated two-trace 5-lead ECG
- SpO₂ and pleth waveform
- NIBP
- Invasive arterial pressure and waveform
- Temperature
- Parameter selection in a clearly labelled **PARAMETERS** setup drawer
- One-time first-use hint pointing users to the parameter selector
- One-button generation of coherent random observation sets
- Layout expands across laptop, desktop and larger displays
- Dedicated edge-to-edge phone-landscape layout
- Full-screen mode
- No server, database, login, patient data or external dependencies

## Run locally

Open `index.html` in a modern browser.

## Recommended deployment

Store the source in a GitHub repository and connect that repository to Cloudflare Pages. Attach `obvs.onlyhems.com` to the Pages project as a custom domain. Cloudflare then serves the app directly at the custom hostname, which remains visible in the browser address bar.

## Important

Educational simulation only. This is not medical software and must not be used for patient care.
