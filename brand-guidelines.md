# 50skills Brand Guidelines

> Extracted from: `assets/brand stuff/50skills brand guide.pdf`  
> Visual reference (colour swatches, gradient samples, logo examples): see the PDF and `assets/brand stuff/50skills AI gradient.png`

---

## Colours

### Primary Colours
Used the majority of the time. Stick to Indigo and Blue ranges as the base.

| Name       | Hex       | Use                          |
|------------|-----------|------------------------------|
| Indigo5    | `#EFECFE` | Light backgrounds, fills     |
| Indigo400  | `#23004E` | Primary dark / headlines     |
| Blue5      | `#F2F6FE` | Light backgrounds, fills     |
| Blue400    | `#152663` | Primary dark / navy          |

### Secondary / Highlight Colours
Used as accents and pops of colour on top of primary colours. Use selectively.

| Name        | Hex       |
|-------------|-----------|
| Green       | `#2BF8B3` |
| Orange      | `#E97C1D` |
| Purple      | `#6E5DC6` |
| Blue        | `#337FFF` |

### Gradient
The brand gradient is a **2-stop** gradient used softly and sparingly — primarily for backgrounds to create depth. Also used for text accents and UI highlights.

- **Colours:** `#63D6FA` (cyan) → `#E039CE` (magenta/pink)
- **Direction:** typically 135deg
- **Rule:** soft and subtle — not heavy or dominant

> Note: The investor deck uses a purple-shifted variant (`#6B2FD9 → #E039CE`) as the gradient feels more on-brand in the context of dark backgrounds and text accents. Both are acceptable depending on context.

### Deck CSS Tokens (for reference)
```css
--purple:   #23004E;   /* Indigo400 */
--navy:     #152663;   /* Blue400 */
--light:    #EFECFE;   /* Indigo5 */
--accent:   #6B2FD9;   /* close to brand secondary purple #6E5DC6 */
--muted:    #5A5472;   /* body text / metadata */
--gradient: linear-gradient(135deg, #6B2FD9 0%, #E039CE 100%);
```

---

## Typography

### Fonts
| Role      | Font       | Notes                                      |
|-----------|------------|--------------------------------------------|
| Headlines | **Nohemi** | All display text, titles, large numbers    |
| Body      | **Work Sans** | Body copy, labels, metadata, captions  |

### Spacing
- Line spacing should match type size (e.g. 40px font → 40px line height)
- The deck uses `line-height: 1.0` for large display text and `line-height: 1.5–1.65` for body

### Font files
- Nohemi variable font: `assets/fonts/Nohemi-VF.ttf` (100–900 weight range)
- Work Sans: loaded from Google Fonts

---

## Logo

### Usage rules
- Always maintain safe space — at least **1× the logo height** clear on all sides
- The **symbol** (icon only) is used for favicons and profile pictures where the full logo doesn't fit
- The **Journeys** and **Hire** sub-logos are used inside the products only — not in external marketing
- The symbol can be used as a repeating **pattern** for backgrounds

### Don'ts
- Don't squeeze or distort the logo
- Don't remove the symbol from the wordmark
- Don't outline the logo
- Don't stack the logo

---

## AI Icon
- **On a light background:** use gradient version or Indigo400
- **On Indigo5 background:** use Indigo5 version

---

## Photography

### Style
- **No stock photos** — use original imagery that depicts how 50skills users, employees, and businesses benefit from the product
- Photos should have **curved/rounded edges** where possible
- Extra graphics (e.g. action cards) can be overlaid on photos

### The 4 character types
1. **AI / Technology** — abstract, tech-forward
2. **HR / Stress-free** — calm, in-control
3. **Too busy / Needs help** — relatable, overwhelmed
4. **Optimistic and bright** — positive outcomes

### Photo library
Available in Figma:  
`https://www.figma.com/design/OOcnLjFvKSLJHMlBCdzfIB/Photos-of-People`

---

## Tone of Voice

> "We are on a mission to transform efficiency with AI and workflow automation. Efficiency isn't just about saving time. It's about making work easier, smoother, and even a little fun. It's about working smarter, not harder, so you can focus on the things that actually make a difference."

- Confident but not corporate
- Clear and direct
- Human and grounded — not overly technical
