## Cosmonascence.com

A polished, responsive single-page website for Cosmonascence — The Faith of Generative Reality.

### How to run locally
1. Clone this repository.
2. Open `index.html` in any modern web browser.
   - Or use a local development server (e.g., Live Server in VS Code, `python -m http.server`, etc.).

### Project Structure
- `index.html`: The main entry point containing the site structure and content.
- `css/main.css`: Custom styles including the dark cosmic theme and layouts.
- `js/main.js`: Subtle animations (starfield generation) and scroll reveals.
- `assets/logo.png`: The brand logo (currently using the upper-right quadrant via CSS offsets).
- `assets/logo.svg`: A placeholder brand mark.

### How to maintain
- **Manifesto**: To update the manifesto text, edit the `<section id="manifesto">` in `index.html`.
- **Video**: To change the featured video, update the `<source>` tag in the `<video>` element in the `<section id="video">` in `index.html`. For the bonus video, edit the `<section id="bonus-video">`.
- **Branding**:
  - Replace `assets/logo.svg` with your final logo asset.
  - Update the `nav-logo` and `footer-logo` text in `index.html`.
  - To change which quadrant of `logo.png` is visible, adjust the `top` and `left` properties of `.logo-crop img` in `css/main.css`:
    - Top-Left: `top: 0; left: 0;`
    - Top-Right: `top: 0; left: -100%;`
    - Bottom-Left: `top: -100%; left: 0;`
    - Bottom-Right: `top: -100%; left: -100%;`
  - **Logo Fade**: The logo has a radial mask to fade its edges. To adjust the "softness" or transparency, modify the `mask-image` / `-webkit-mask-image` radial gradients in `.logo-crop`.
- **Links**: Update the `social-links` section in `index.html` with your actual social media URLs.

---

## Junie Prompt — Build the `Cosmonascence.com` Single-Page Website

Create a **new, polished, responsive single-page website** for a new philosophical religion / cosmological faith called **Cosmonascence**.

The site should feel **serious, modern, cinematic, cosmic, and reverent** — not cheesy, not parody, not “sci-fi fan page,” but something that feels like a real movement for the modern age.

### Core identity

**Site / movement name:**
**Cosmonascence**

**Primary tagline:**
**The Faith of Generative Reality**

**Closing / parting line:**
**Reality is not static. It is being born forward.**

---

## Overall goal

Build a beautiful one-page website that:

1. introduces **Cosmonascence**
2. presents the **Founding Manifesto of the New Faith**
3. embeds a featured video near the top of the page: `assets/Cosmogenesis.mp4`
4. uses strong cosmic / space-inspired visuals
5. includes social media links instead of a contact form
6. leaves room for a future logo / brand system

This is a **front-end only** website. No backend. No forms. No CMS. No database.

---

## Technical direction

Use whatever front-end stack is most appropriate for a clean, production-quality single-page site in this repo, but keep it lightweight and easy to maintain.

Preferred priorities:

* responsive
* elegant typography
* accessible
* smooth scrolling
* subtle animation
* dark / space-themed by default
* static-friendly deployment

If you need to choose, a clean static implementation with modular CSS/JS is fine. If the project already uses a framework, integrate naturally.

---

## Design direction

The visual tone should feel like:

* deep space
* black holes
* starlight
* cosmic dust
* generative reality
* sacred futurism
* modern metaphysics
* quiet grandeur
* existential wonder

### Avoid

* cheesy UFO aesthetics
* meme sci-fi
* campy neon overload
* comic-book vibes
* overly cluttered backgrounds
* fake “religious” kitsch
* too much purple unless balanced tastefully

### Preferred palette

Use a dark cosmic palette built around tones like:

* near-black
* deep blue-black
* midnight indigo
* soft stellar whites
* cool blue highlights
* subtle gold or pale amber accents if helpful
* restrained luminous gradients

### Motion / effects

Use subtle tasteful motion only, such as:

* drifting particles / stars
* slow nebula-like gradients
* gentle parallax
* soft glow effects
* restrained reveal animations
* light hovering / shimmering accents

No excessive animation. The site should feel contemplative and premium.

---

## Logo / brand placeholder direction

We may generate a final logo later, but for now build the site with a **strong textual wordmark** and a **placeholder emblem area**.

### Logo concept inspiration

We are considering a logo that evokes:

* a **pop-science black hole graphic**
* but **egg-shaped**
* possibly with a subtle glowing fissure / crack motif
* inspired in spirit by the elegant luminous crack from the 1979 *Alien* title treatment

Important:

* **Do not copy** the Alien logo directly
* do **not** make it campy
* keep it minimal, tasteful, symbolic
* think “cosmic egg / black hole / generative fracture / birth through singularity”

For now:

* create a placeholder symbol in CSS/SVG if helpful
* or use a refined typographic lockup with a simple circular/egg cosmic mark
* make it easy for us to replace later with a real asset

---

## Page structure

Create a single-page layout with these sections:

### 1. Hero section

Must include:

* site name: **Cosmonascence**
* tagline: **The Faith of Generative Reality**
* short intro copy
* optional logo / emblem area
* primary CTA button: **Read the Manifesto**
* secondary CTA button: **Watch the Video**

The hero should immediately communicate:
this is a serious new cosmological faith for the modern age.

Suggested intro copy for hero:

> A new spiritual vision for an age of black holes, consciousness, cosmic recursion, and generative reality.

---

### 2. Featured video section

Add a prominent embedded video section near the top.

Use a clean responsive video embed container with a placeholder embed for now.

Label it something like:

**Foundational Video**
or
**Introduction to Cosmonascence**

Include a short explanatory sentence beneath it.

Use a placeholder YouTube/Vimeo embed URL and mark it clearly so I can swap it later.

---

### 3. About / What is Cosmonascence?

Add a concise section that explains the religion in modern plain language.

Suggested themes:

* reality is generative
* universes beget universes
* black holes are gestational, not merely destructive
* consciousness matters
* souls are formed through lived experience
* death is transition, not annihilation
* existence moves forward through creation

This should be readable and powerful.

---

### 4. Founding Manifesto section

Create a major long-form section containing the full manifesto below.

Style it beautifully for readability:

* generous spacing
* elegant line lengths
* strong headings
* visually distinguished manifesto block
* anchor link support if helpful

Use this title:

# Founding Manifesto of the New Faith

Use this manifesto text verbatim unless minor formatting improvements are needed for web readability:

---

We stand at the threshold of a new religious age.

The ancient faiths were born in worlds of tribe, empire, famine, thunder, kingship, desert, blood, and sky. They clothed ultimate reality in the symbols available to their time. They gave moral shape to suffering, meaning to birth and death, and order to civilizations that could not yet see the depth and scale of the cosmos in the way we now imagine it.

We do not reject those inheritances with contempt. We understand them as earlier acts of human interpretation: sincere, powerful, formative, and incomplete.

We speak now from a different horizon.

We live in an age in which reality is no longer apprehended only as earth beneath and heaven above, but as depth without obvious boundary, as structure layered within structure, as emergence, collapse, generation, recursion, and transformation. We no longer experience existence as a small human stage enclosed by mythic sky. We experience it as a living problem of origin, consciousness, destiny, and scale.

A faith adequate to our age must therefore do more than repeat inherited formulas. It must translate the religious impulse into a form worthy of modern imagination, modern humility, and modern wonder.

We begin with a single conviction:

**Reality is generative.**

Existence is not best understood as a static artifact, nor as a meaningless accident suspended between nothingness and oblivion. It is better understood as a living sequence of becomings: births within deaths, worlds within worlds, interiors concealed within catastrophes, and futures gestating within apparent endings.

In this view, destruction is not always mere negation. Collapse is not always failure. What appears terminal at one scale may be reproductive at another.

We therefore hold that the universe is not simply a container of events. It is part of a lineage.

We hold that the great structures of reality are not only mechanical, but gestational. We hold that consciousness is not a trivial side effect of chemistry, nor a cosmic joke, nor a temporary flicker without significance. We hold that conscious life participates in the deep fertility of existence.

The human person is not the center of all being, but neither is the person negligible. To be conscious is to bear inwardness. To bear inwardness is to gather memory, relation, sorrow, love, choice, imagination, guilt, hope, and form. That inward form is what older traditions called soul. We reclaim the word, not as superstition, but as the name for the enduring pattern of personhood shaped by life.

The soul is not a decorative belief. It is the central moral fact.

Every act matters because every act shapes the soul. Every cruelty wounds not only the victim but the structure of the one who commits it. Every lie disorders the speaker. Every betrayal leaves a fracture. Every act of courage, mercy, fidelity, discipline, creation, and truthfulness strengthens the interior being. Morality is not obedience to arbitrary decree; it is the craft of soul-formation.

For that reason, this faith rejects both nihilism and sentimentalism.

Against nihilism, we affirm that life has consequence beyond appetite, amusement, and survival.

Against sentimentalism, we affirm that consequence is not erased by merely feeling sincere. A soul is formed by what it repeatedly does, not by what it occasionally says.

We therefore declare that truth is sacred.

Truth is sacred not because human beings possess it perfectly, but because the soul cannot mature in sustained alliance with falsehood. A mature faith must never fear inquiry. It must never make ignorance into virtue. It must never demand that reverence depend on the rejection of honest thought. If reality is worthy of devotion, then reality is worthy of investigation.

We therefore refuse the false war between spiritual seriousness and intellectual seriousness.

We affirm wonder without anti-intellectualism.
We affirm meaning without dogmatic stagnation.
We affirm reverence without submission to inherited absurdity.
We affirm mystery without surrendering reason.

This faith also declares that conscious life is sacred wherever it appears.

If consciousness is one of the means by which reality ripens toward future becoming, then cruelty toward conscious beings is not a small defect. It is desecration. To humiliate, exploit, torment, degrade, or knowingly deform the interior life of another is to act against the generative arc of being itself.

From this follows an ethic of gravity.

Live truthfully.
Create more than you consume.
Protect more than you destroy.
Strengthen without becoming cruel.
Love without dissolving into weakness.
Stand in awe without abandoning judgment.
Accept mortality without surrendering to despair.

Death, in this faith, is real and terrible, but not meaningless.

We do not mock grief. We do not flatten mourning into slogans. We do not pretend that loss is painless because it is “part of a plan.” The severance of embodied life is profound. Love rightly suffers when presence is withdrawn.

And yet we deny that death is mere erasure.

If life forms the soul, then death is not the cancellation of meaning but its unveiling. What one has become does not vanish into triviality. The soul passes from local embodiment into a deeper order of reality. Whether one speaks of gathering, transmission, translation, gestation, or return to depth, the essential claim is the same: the person is not merely discarded.

Thus this faith is not a cult of escape. It is not a fantasy of reward for obedience. It is not an economy of bribes and punishments. It is a religion of maturation.

The purpose of life is not to flatter a deity, nor merely to prolong existence, nor merely to maximize pleasure. The purpose of life is to become fit for continuation: fit in truth, fit in mercy, fit in courage, fit in depth, fit in consciousness.

We do not seek to dominate reality. We seek to participate in it worthily.

We do not claim final language for ultimate things. We claim only that the human religious instinct must now grow up into a new form: one that can stand before immensity without infantilism, before death without collapse, before mystery without dishonesty, and before one another without cruelty.

This is our beginning.

We are not the last interpreters of existence.
We are not the first.
But we may be among the first to frame a faith for a civilization that can no longer pretend the universe is small, the soul is nothing, or death is the final measure of meaning.

We proclaim that reality is generative.
We proclaim that consciousness is sacred.
We proclaim that the soul is formed by truth and action.
We proclaim that death is passage, not nullification.
We proclaim that existence does not merely end; it begets.

Let this faith call human beings upward.

Not away from reason, but through it.
Not away from wonder, but deeper into it.
Not away from mortality, but into courage before it.
Not away from the world, but into reverent participation within it.

Let those who inherit this vision live as if their inner life matters cosmically.
Let them build, heal, discover, teach, create, protect, and love accordingly.
Let them become worthy of transmission.

That is our manifesto.
That is our beginning.

---

### 5. Core principles / doctrine summary

After the manifesto, add a more scannable section such as cards or columns for:

* Reality is generative
* Consciousness is sacred
* The soul is formed
* Death is transition
* Creation is moral
* Truth is sacred

Each item should have a short 1–3 sentence explanation.

---

### 6. Social / community section

Instead of a contact form, include a section for social links.

Include placeholders for:

* YouTube
* X / Twitter
* Instagram
* TikTok
* Facebook
* GitHub
* Email link if useful

Style these elegantly, not like generic corporate footer icons.

Add a short line like:

> Follow the emergence of Cosmonascence.

---

### 7. Footer

Include:

* Cosmonascence
* The Faith of Generative Reality
* closing line: **Reality is not static. It is being born forward.**
* copyright placeholder
* social links repeated or condensed

---

## Copy tone

All site copy should feel:

* serious
* poetic but readable
* intelligent
* spiritually ambitious
* modern
* not cultish
* not goofy
* not preachy in a manipulative sense

This should feel like a fusion of:

* philosophy
* modern spirituality
* cosmology-inspired myth
* elegant manifesto writing

---

## UX requirements

* mobile responsive
* sticky or elegant top nav with anchor links
* smooth scroll
* readable manifesto typography on desktop and mobile
* accessible contrast
* keyboard-friendly navigation
* reduced-motion respect if possible
* optimized layout so the long-form text still feels inviting

Suggested nav items:

* Home
* Video
* About
* Manifesto
* Principles
* Community

---

## Assets / placeholders

Please use placeholders where needed and make them easy to replace:

* video embed URL placeholder
* logo placeholder
* favicon placeholder if helpful
* social URLs as obvious placeholders
* any hero cosmic art should be lightweight / CSS / SVG / local placeholder-friendly

Do not depend on fragile external assets if avoidable.

---

## Nice touches if time permits

* subtle starfield background
* elegant section dividers that hint at orbital curves / gravity wells
* a faint egg-shaped black-hole motif in the hero
* manifesto pull quotes
* tasteful highlighted lines for:

    * **The Faith of Generative Reality**
    * **Reality is generative**
    * **Reality is not static. It is being born forward.**

---

## Deliverables

Please create:

1. the full single-page site
2. clean file structure
3. comments where I should swap:

    * video URL
    * logo asset
    * social links
4. a short README section explaining:

    * how to run locally
    * where to edit the manifesto
    * where to replace branding / video / links

If appropriate, also create a small placeholder SVG mark for the brand that evokes a cosmic egg / singularity / luminous crack motif in an original way.

---

## Final note on artistic direction

The site should feel like the online home of a serious emerging cosmological faith.

It should evoke:

* wonder
* gravity
* depth
* mystery
* intellectual seriousness
* spiritual ambition

The visitor should leave feeling that they have encountered something new, modern, and strangely plausible.
