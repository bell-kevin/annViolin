# annViolin

Presentation materials for **"The Origin of the Modern Violin"** — a 15-minute talk given by
Ann Peterson at the Sempre Music Club, Ogden, Utah, 2026.

## Live

The slideshow is published with GitHub Pages and opens straight into the deck:

- **Slideshow — <https://bell-kevin.github.io/annViolin/>**
- **Speaking script — <https://bell-kevin.github.io/annViolin/violin-script.html>**

## Contents

| File | What it is |
| --- | --- |
| [`index.html`](index.html) | The slideshow — 20 slides, self-contained; served as the site root |
| [`violin-script.html`](violin-script.html) | The speaking script as a web page, with a live pace timer |
| [`violin-script.md`](violin-script.md) | The same script in Markdown, for printing or editing |

All three are standalone. Nothing to build, nothing to install — double-click an HTML file and it
runs, online or off. The only network request is to Google Fonts; the pages fall back to Georgia
if that fails.

`.nojekyll` disables Jekyll processing so Pages serves the files exactly as committed.

## Running the slideshow

Open the [live site](https://bell-kevin.github.io/annViolin/) (or `index.html` locally) and press
<kbd>F</kbd> for fullscreen.

| Key | Action |
| --- | --- |
| <kbd>→</kbd> <kbd>Space</kbd> <kbd>↓</kbd> | Next slide |
| <kbd>←</kbd> <kbd>↑</kbd> <kbd>Backspace</kbd> | Previous slide |
| <kbd>O</kbd> | Outline — jump to any slide by title |
| <kbd>F</kbd> | Toggle fullscreen |
| <kbd>Home</kbd> / <kbd>End</kbd> | First / last slide |

Clicking anywhere advances; clicking the left sixth of the screen goes back. Swipe works on
tablets. `Ctrl+P` prints one slide per page for handouts. The current slide is kept in the URL
hash, so reloading returns you to the same place.

## Using the script

Open `violin-script.html` and press <kbd>S</kbd> (or click **Start**) to run the pace timer. It
highlights the section you should be reading at that moment and shows how much time is left, so
you can tell at a glance whether you are drifting.

- **About 2,100 spoken words**, about 14:30–15:05 depending on pace.
- Times in the left rail are **cumulative** — where to be when you *start* that slide.
- Slide 7 cues Ann to point to the violin in the enlarged painting detail and pause briefly.
- Slides 11 (Brescia) and 18 (the timeline) are marked **cut if long**; dropping both saves
  roughly 70 seconds.
- <kbd>A+</kbd> / <kbd>A−</kbd> adjust the type size, remembered per browser.

## The talk

The argument, in short: the violin is unusual among instruments in having no gradual childhood.
It appears in the Po valley around 1530 essentially finished — a *synthesis* of the rebec's
tuning in fifths, the medieval fiddle's body, and the lira da braccio's playing position, and
specifically **not** a descendant of the viol, which is a same-era cousin built for a different
job. Andrea Amati fixes the form in Cremona; the plague of 1630 forces the Amati workshop to take
apprentices from outside the family, which is how the craft spreads.

Then the payoff on the word *modern*: almost no Stradivari is in the condition Stradivari left it.
Between roughly 1780 and 1830 nearly every surviving old Italian violin was rebuilt with a longer,
back-tilted neck and a heavier bass bar, to carry more tension and more sound into bigger halls.
The instrument in the case is a Renaissance object wearing a Romantic conversion.

Three hand-drawn SVG diagrams carry the parts prose is slow at: violin vs. viol anatomy, the
Cremonese apprenticeship chain around the 1630 plague, and the baroque/modern setup comparison.

### A note on contested points

Two claims are deliberately presented as unsettled rather than as the traditional romantic story:

- Stradivari's apprenticeship under Nicolò Amati is **traditional but disputed**, and the diagram
  on slide 13 marks that link with a dashed line.
- The "secret of Stradivari" theories — varnish, chemical treatment of the wood, Little Ice Age
  spruce — are presented as unproven, with the post-2010 blind playing tests as the counterweight.

## Sources

- David Schoenbaum, *The Violin: A Social History of the World's Most Versatile Instrument* (2013)
- Peter Walls, "Violin," *Grove Music Online*
- Philibert Jambe de Fer, *Epitome musical* (Lyon, 1556)
- Claudia Fritz et al., "Player preferences among new and old violins," *PNAS* (2012), and the
  Paris follow-up study (2014)
- The Ashmolean Museum, Oxford; the National Music Museum, Vermillion, South Dakota

## Artwork

Slide 7 includes Gaudenzio Ferrari's *Madonna of the Orange Tree* (1529–30), in San Cristoforo,
Vercelli, alongside an enlarged detail of the musician angels so the violin is easy to see.
Both JPEGs are embedded in `index.html`, so the slideshow remains a single file that works offline.

Public-domain reproductions from Wikimedia Commons:

- [Full painting](https://commons.wikimedia.org/wiki/File:La_Madonna_degli_aranci.jpg)
  — 1,234 × 2,216 pixels; public domain (PD-old-100).
- [Musician-angel detail](https://commons.wikimedia.org/wiki/File:La_Madonna_degli_aranci_-_Putti.jpg)
  — 1,235 × 686 pixels; public domain (PD-Art / PD-old-100). The source page credits
  Renato Meucci, *Un corpo alla ricerca dell'anima…*, Saggi–Essays, Cremona, 2005, p. 68.

## Known gaps

Other artworks named in the talk could still be added: Ferrari's 1535 Saronno cupola, an Andrea
Amati from the Charles IX set, and a Stradivari label. Slides 7, 10 and 14 are the natural homes
for those.
