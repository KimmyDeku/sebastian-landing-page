# Sebastian — Premium AI Butler Website

A responsive, cinematic Sebastian landing website based on the Victorian digital-butler requirements and the supplied butler-hand/tray reference image.

## Included
- Responsive desktop, tablet and mobile layouts
- Fixed responsive navigation: Home, About, Services, Contact Us, Sign Up, Login
- Cinematic hero
- Sticky scroll-driven butler tray storytelling section with 10 services
- Responsive mobile adaptation of the tray experience
- Victorian bowtie branding and restrained motion
- Male browser text-to-speech demo
- Sign-up/login modal UI
- Trust and confirmation principles
- Accessibility and reduced-motion support

## Run
No build step is required. Open `index.html` in a modern browser.

For best results, run a local server from this directory, for example:

```bash
python -m http.server 8080
```

Then visit `http://localhost:8080`.

## Image
`assets/butler-tray.png` is a transparent-background version of the supplied butler/tray reference image, prepared for the dark website composition.

## Production integration
The Sign Up/Login forms are intentionally UI-only. Connect them to Sebastian's authentication/backend implementation before production. The male voice demo uses browser speech synthesis; replace it with a server-side/professional TTS provider for production voice quality.
