# Furkan Söker, developer

Personal portfolio site. One page, plain HTML, CSS and JavaScript, no build step.

- **Scroll film hero:** a short AI-generated video plays forward as you scroll down and backward as you scroll up. Phones and reduced-motion visitors get a still hero instead.
- **Nine projects:** YumYumAI, ExcelToWeb, Paperpin, Whey Protein, Kavrul, AutoForge, AI Growth OS, FoodOrder and WordCards.
- **English and Turkish:** switch with the EN / TR button. The choice is remembered.
- **Hold to compile:** a small press-and-hold moment in the "How I work" section.

## Run locally

```bash
python3 -m http.server 5190
```

Then open http://127.0.0.1:5190. Opening `index.html` directly works too, but browsers block the video fetch on `file://`, so you see the still hero.

## Notes

- The hero film is generated with AI. Every project screenshot is real.
- The Whey Protein 3D tub model is by Naseem on Sketchfab, licensed CC BY 4.0.
- Before deploying, set the `og:image` and `og:url` tags (marked `DEPLOY STEP` in `index.html`) to the live URL.
