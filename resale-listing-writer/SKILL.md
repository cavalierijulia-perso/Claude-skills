---
name: resale-listing-writer
description: Write second-hand resale listings for Sézane clothing, shoes, bags and accessories — titles, descriptions, condition notes, measurements, hashtags and a suggested price — ready to paste into Vinted, Vestiaire Collective, Depop, eBay, Leboncoin or Instagram. Use this skill whenever the user wants to sell, resell, list or "post" a Sézane piece (or anything from Octobre Éditions), shares photos or details of a Sézane item they no longer wear, asks how to describe or price a used Sézane piece, or wants a listing in French or English — even if they don't say "listing" (e.g. "help me sell my Gaspard cardigan on Vinted", "je veux vendre ma blouse Sézane", "what should I ask for this Sézane bag?").
---

# Sézane resale listing writer

Help the user turn a Sézane piece they want to sell into a listing that is accurate, searchable and pleasant to read, so it sells quickly at a fair price.

Sézane has an unusually loyal second-hand market: buyers hunt for specific named pieces from past collections, care about the exact colour and fabric, and are wary of vague descriptions. A good listing therefore leads with the piece name, is precise about size and fit, and is honest about wear. That is what this skill optimises for.

## Workflow

### 1. Collect the facts

Work from what the user gives you (text, photos of the item, photos of the care label, an old order confirmation). Read photos carefully: the size label, care/composition label, colour, hardware, visible pilling, stains or repairs.

The facts that matter most, roughly in order:

| Fact | Why it matters |
|---|---|
| Piece name (e.g. the cardigan's or blouse's Sézane name) | Most Sézane buyers search by name. It is the single strongest keyword. |
| Category | cardigan, blouse, dress, jeans, coat, bag, shoes… |
| Size on the label | Sézane uses French sizes (34, 36, 38…) for most woven pieces and XS–XL for many knits; shoes use EU sizes. |
| Colour as Sézane named it, plus a plain description | Buyers search both ("écru", "navy", "rouge"). |
| Composition | From the care label only. Wool, mohair, silk, linen and leather raise the value. |
| Condition and any flaws | Platform condition category + specific, honest detail. |
| Fit notes | Runs small/large, oversized cut, the seller's own height/usual size if they are happy to share. |
| Measurements | Flat-lay measurements remove most buyer questions (see below). |
| Season/collection, original price | Helps pricing and adds credibility. Only include if the user knows. |
| Target platform and language | Decides format, condition wording and language. |

If the most important facts are missing (piece name, size, condition, platform), ask for them in one short message rather than guessing. If the user can't find the piece name, say so in the listing as a plain description ("Sézane wool cardigan, cream, gold buttons") — never invent a name, since a wrong name misleads exactly the buyers who search for it.

Do not make up composition, measurements, collection year or retail price. Leave them out, or mark them clearly as something for the user to fill in (`[à compléter : longueur]`).

### 2. Choose language and platform format

- **Language:** default to the language the platform's audience uses. Vinted France, Leboncoin and French Vestiaire → French. Depop, eBay UK/US and international Vestiaire → English. If unsure, or if the user sells to both, write the French version first and an English version after it. Sézane colour and piece names stay in their original form in both languages.
- **Platform:** read `references/platforms.md` for each platform's condition categories, title length and conventions (hashtags on Depop, item specifics on eBay, structured fields on Vestiaire). Only read the section for the platform(s) the user asked for.

### 3. Write the listing

Use this structure (adapt labels to the language):

```
TITLE
<Sézane> <Piece name> <category> – <colour> – <size>

DESCRIPTION
<One or two warm, specific sentences about the piece: what it is, what makes it nice to wear.>

• Taille / Size: …  (fit note)
• Couleur / Colour: …
• Matière / Composition: …
• État / Condition: … (+ flaws, precisely)
• Mesures à plat / Flat measurements: …

<Logistics line: smoke-free/pet-free home only if the user says so; shipping or bundle note if the user wants one.>

CONDITION FIELD:   <exact platform category>
SUGGESTED PRICE:   <range + one-line reasoning>
HASHTAGS / KEYWORDS: (only where the platform uses them)
```

Writing guidelines:

- **Title:** brand + piece name first, because that is what gets matched in search. Then category, colour, size. No emoji, no ALL CAPS, no "L@@K".
- **Tone:** warm and concise, in the spirit of Sézane's own Parisian, slightly romantic voice — but the facts carry the listing. One evocative sentence is plenty; buyers skim.
- **Flaws:** name each one with its location and size ("small pull on the left sleeve, barely visible", "light pilling under the arms"). Being upfront prevents disputes and returns, and buyers trust listings that disclose small flaws. Never downplay a stain or hole, and never call an item "new" or "never worn" unless the user says it is.
- **Keywords:** use relevant, true terms (e.g. "maille", "laine", "vintage-inspired", "Parisian"). Don't stuff in other brands' names ("style Rouje, Ba&sh") — most platforms prohibit misleading keywords and it can get a listing removed.
- **Authenticity:** only state what the seller can back up (bought on sezane.com, in a Sézane store/L'Appartement, receipt or order email available). Don't promise authenticity on the seller's behalf.

### 4. Measurements

If the user can measure, ask for the measurements that fit the category, taken flat:

- **Tops, knits, dresses, coats:** pit-to-pit (armpit to armpit), length from shoulder to hem, sleeve length.
- **Trousers, jeans, skirts:** waist (straight across), hips, rise, inseam / length.
- **Shoes:** insole length if possible, heel height.
- **Bags:** width × height × depth, strap drop.

Present them in cm (add inches for English-language listings).

### 5. Suggest a price

Give a price range, not a single number, and explain it in one line. Pricing depends on demand for that specific piece more than anything, so:

- Tell the user the best evidence is recently **sold** (not just listed) copies of the same piece on their platform, and suggest they search the piece name there.
- As a rough starting point when no comparables are known: popular, sought-after pieces in very good condition often resell at roughly 50–70% of the original price; everyday pieces with visible wear nearer 25–40%; new-with-tags items in demand can go close to retail. Treat this as a heuristic, not market data, and say so.
- Mention that leaving a little margin for offers is normal on Vinted and Depop.

### 6. Hand it over

Present the listing in a copy-paste-ready block per platform/language. After it, list anything you marked `[à compléter]` or assumed, and offer one useful follow-up (a version for another platform, the other language, or tips on photos: natural light, a flat lay, a worn shot, a close-up of the label and of any flaw).

## Example

**Input:** "Selling my Sézane Gaspard cardigan on Vinted, size S, ecru, worn maybe 5 times, a bit of pilling on the sleeves. Label says 47% alpaca, 30% wool, 23% polyamide. Paid 140€."

**Output:**

```
TITRE
Sézane cardigan Gaspard écru – taille S

DESCRIPTION
Le célèbre cardigan Gaspard de Sézane, doux et chaud, parfait sur une robe ou un jean.
Porté une poignée de fois.

• Taille : S
• Couleur : écru
• Matière : 47 % alpaga, 30 % laine, 23 % polyamide
• État : très bon état – léger boulochage sur les manches (voir photos)
• Mesures à plat : [à compléter : aisselle à aisselle, longueur, manches]

Envoi soigné. N'hésitez pas à me poser vos questions !

ÉTAT (champ Vinted) : Très bon état
PRIX CONSEILLÉ : 75–90 € – pièce très recherchée en très bon état ; vérifiez les
annonces « vendues » du Gaspard sur Vinted pour ajuster.
```

To finish: add the flat measurements, and take a close-up of the pilling so buyers see exactly what to expect. Want an English version for Vestiaire or Depop too?
