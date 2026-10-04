# Abhishek — Personal Portfolio Plan

## Approved scope

Build a professional, responsive personal portfolio website for Abhishek. The site is positioned as a sample freelance photographer portfolio because no specific profession or work history was provided. It includes a hero, clear navigation, About Me section, sample photography portfolio, and contact form.

## Design direction

- **Design movement:** Contemporary editorial portfolio with a hint of Swiss poster design and analog contact-sheet culture.
- **Core principles:** Strong typographic contrast, asymmetrical composition, generous breathing room, and photography treated as the main voice.
- **Color philosophy:** Warm butter yellow creates daylight and optimism; vivid vermilion red adds energy and a recognizable signature; ink black anchors the system and gives the work room to breathe.
- **Layout paradigm:** A horizontal editorial rhythm with split-color bands, offset captions, and intentionally uneven gallery framing rather than a centered card grid.
- **Signature elements:** Numbered section markers, red underline rules, and small yellow metadata tabs.
- **Interaction philosophy:** Navigation feels like moving through a printed zine: anchors are direct, hover states are tactile, and the contact form responds with a clear human confirmation.
- **Animation:** Gentle reveal-on-scroll, a soft hero image drift, and quick underline/arrow transitions. Motion stays restrained so the photography remains primary.
- **Typography system:** `DM Sans` for utility and body copy, `Space Grotesk` for display headlines and navigation. Headlines use tight tracking and large responsive sizing; labels use uppercase with generous letter spacing.
- **Brand essence:** A photographer who turns passing light into lasting stories for people, places, and brands. Personality: observant, cinematic, warm.
- **Brand voice:** Direct, curious, and quietly confident. Example lines: “Let’s make something worth remembering.” / “The best frames usually happen between the planned ones.”
- **Wordmark & logo:** A compact monogram built from an offset red `A` and yellow square, paired with a small all-caps wordmark.
- **Signature brand color:** Vermilion `#e4472e`.

## Project structure

- `index.html` — semantic shell, metadata, and font loading.
- `src/main.js` — page content, interaction behavior, form state, and icon markup.
- `src/styles.css` — responsive design tokens, layout, motion, and component styling.
- `public/manus-routes.json` — current page route declaration.
- `public/assets/` — managed-storage image slots used by the gallery and hero.
- `app.config.ts` — project logo metadata for the platform.

## Technical decisions

- Use a small Vite-powered vanilla frontend to keep the portfolio fast and easy to hand off.
- Keep the contact form client-side in this first version because no server, database, or notification channel was requested; show validation and a success state without claiming messages are actually delivered.
- Use responsive CSS breakpoints for phone, tablet, and desktop layouts.
- Use the managed image URLs returned for the planned hero and gallery assets.
