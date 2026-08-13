# Omolara Suliyat Ojo — Portfolio

Personal portfolio site for **Omolara Suliyat Ojo**, a Customer Support and Operations
Executive based in Lagos, Nigeria, with experience in live chat and CRM systems,
client communication, social media management, and administrative operations.

## About this site

A single, self-contained page — `index.html`. No build step, no framework, no
dependencies beyond the Inter webfont. Open the file in a browser and it works.

- Light theme, responsive down to mobile
- Print stylesheet — the "Save as PDF" button produces a clean CV
- Semantic HTML with Open Graph tags for link previews

## Publishing it

1. Create a repository on GitHub. To get a clean address like
   `omolara.github.io`, name the repo `<username>.github.io`; any other name
   publishes to `<username>.github.io/<repo-name>/`.
2. Upload `index.html` and this `README.md` to the repository root.
3. In the repository, go to **Settings → Pages**, set **Source** to
   *Deploy from a branch*, choose `main` and `/ (root)`, and save.
4. The site is live within about a minute. Any later push republishes it.

## Editing

All content lives directly in `index.html`. Everything is plain HTML in clearly
labelled sections (`<!-- HERO -->`, `<!-- EXPERIENCE -->`, and so on), so text can be
updated by editing it in place. Colours, spacing, and the accent colour are CSS
variables in the `:root` block at the top of the `<style>` tag.

The three figures in the hero (241%, 2,200+, 70%) are in the `<!-- HERO -->`
section under `class="results"`.

## Note on contact details

The page publishes an email address, a phone number, and a LinkedIn profile.
Anything published to GitHub Pages is public and can be indexed by search
engines, so confirm these details should be public before deploying, and remove
any that shouldn't be from the `<!-- HERO -->` and `<!-- CONTACT -->` sections.
