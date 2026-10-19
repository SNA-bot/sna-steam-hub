# SNA Virtual Laboratory & STEAM Hub

Interactive science lab for **Sealed Nectar Academy** — Chemistry modules with animations, quizzes, and simulations.

Single-file static site (HTML + CSS + JS). No build step.

## Live deploy (Vercel)

1. Push this folder to a GitHub repo (e.g. `sna-steam-hub`).
2. In [Vercel](https://vercel.com) → **Add New Project** → import that repo.
3. Framework preset: **Other**.
4. Output / root: leave default (repo root).
5. Deploy.

Your lab will be at something like:

`https://sna-steam-hub.vercel.app`

(or your chosen project name).

## Link from the main SNA website

On [SNA Website](https://sna-website-v-1.vercel.app), add a button or menu item that opens the lab:

```html
<a href="https://YOUR-LAB-URL.vercel.app" target="_blank" rel="noopener">
  Open Science Lab & STEAM Hub
</a>
```

Or use same-tab navigation:

```html
<a href="https://YOUR-LAB-URL.vercel.app">Science Lab</a>
```

### Optional: same domain path

If you prefer the lab under the main site domain later:

- Deploy this project as a Vercel project, **or**
- Copy `index.html` into a folder of the main site repo (e.g. `/lab/` or `/steam-hub/`) and redeploy the main site.

## Modules (Chemistry Lab)

- Introduction to Chemistry, Nature of Matter, Elements  
- Molecules & Atomicity, Particulate Nature, Relative Atomic Mass  
- Compounds, IUPAC Nomenclature, Mixtures  
- Chemical Bonding, Acids/Bases & pH  
- Rates of Reaction, Energy Changes, Mole Concept  
- Organic Chemistry (homologous series, isomerism, reactions, …)  
- Galvanic Cell, Electrolysis, Redox, Electrochemistry  
- Periodic Trends, Periodic Table History  

## Local use

Open `index.html` in any modern browser. No server required.

## Branding

Sealed Nectar Academy — educational use.
