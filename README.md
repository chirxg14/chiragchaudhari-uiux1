# Nidaan – Doctor Appointment Landing Page

**Course task:** UI/UX using Figma (IPS) – Responsive product landing page
**Product:** Nidaan, a fictional online doctor appointment service
**Files:** `index.html` (coded reference of the design), Figma design link:https://www.figma.com/design/GhVRqr0AeQIjcRPm9CWNX8/Untitled?node-id=0-1&t=3I426jZRI8itZRFu-1

## 1. Intended users

| User | Need | How the page helps |
|---|---|---|
| Working adults (25–45) | Can't spend a morning in a clinic queue | Live time slots and a booking card visible in the hero |
| Parents | Need a trusted paediatrician fast | "Verified doctors" card builds trust |
| Families of senior citizens | Book on behalf of parents, keep records | Reminders and records card |
| Clinics (secondary) | Fewer phone calls, fewer no-shows | "For clinics" link in header and footer |

**Primary goal of the page:** get a visitor to press *Book an appointment*.

## 2. Design choices

- **Hero shows the product, not a stock photo.** The booking card (doctor, day, time, confirm) answers "what does this do?" in one look, and it is built entirely from reusable components.
- **Teal + marigold.** Deep teal and ink feel calm and clinical. Marigold is used only for the main action, so the eye always finds the button first.
- **Two typefaces.** Bricolage Grotesque for headings (friendly but confident), DM Sans for body and UI text (very readable at small sizes).
- **Consistent 8-point spacing** and only three corner radii, so the page feels orderly.
- **Plain copy.** Buttons say exactly what happens ("Book an appointment", "Confirm Today, 10:30 AM").
- **Accessibility:** text contrast above 4.5:1, visible focus states, large tap targets, works on mobile.

## 3. Shared styles (create these in Figma first)

### Color styles
| Style name | Hex | Use |
|---|---|---|
| Ink | `#0E2F34` | Headings, dark section |
| Teal | `#14746F` | Brand, icons, selected state |
| Mint | `#E3F1EE` | Icon backgrounds, hero panel |
| Sun | `#F4B13E` | Primary button only |
| Paper | `#F6F8F7` | Page background |
| White | `#FFFFFF` | Cards |
| Muted | `#4F6569` | Secondary text |
| Line | `#D5E3E0` | Borders |

### Text styles
| Style name | Font | Size / line height | Weight |
|---|---|---|---|
| Display/H1 | Bricolage Grotesque | 60 / 64 | Bold |
| Heading/H2 | Bricolage Grotesque | 38 / 44 | Bold |
| Heading/H3 | Bricolage Grotesque | 20 / 28 | Bold |
| Body/Large | DM Sans | 18 / 28 | Regular |
| Body/Regular | DM Sans | 16 / 26 | Regular |
| Body/Small | DM Sans | 14 / 20 | Regular |
| Button | DM Sans | 16 / 24 | Bold |

### Spacing and radius
Spacing: 4, 8, 16, 24, 32, 48, 80. Radius: 10 (chips), 12 (buttons, icons), 16–20 (cards).

## 4. Reusable components (Figma)

1. **Button** – Auto Layout horizontal, padding 14 / 24, gap 8. Variants: `Primary` (Sun fill), `Secondary` (Ink outline), `Small`.
2. **Feature Card** – Auto Layout vertical, padding 28, gap 16, fill container. Contains Icon, H3, Body/Regular.
3. **Nav Link** and **Header** – Auto Layout horizontal, space between, height 80.
4. **Slot Chip** – Variants: `Default`, `Selected` (Teal fill), `Disabled`.
5. **Step Item** – Number circle + H3 + text, vertical Auto Layout.

Make each one a component (Ctrl/Cmd + Alt + K) and use instances everywhere.

## 5. Figma build checklist

- [ ] Frame **Desktop 1440 × auto**, layout grid: 12 columns, margin 120, gutter 24
- [ ] Frame **Mobile 390 × auto**, layout grid: 4 columns, margin 24, gutter 16
- [ ] Create color styles and text styles (section 3)
- [ ] Build the components (section 4)
- [ ] Header: logo, 4 nav links, "Book now" button (Auto Layout)
- [ ] Hero: H1, description, 2 buttons, booking card
- [ ] Features: 3 Feature Card instances in a horizontal Auto Layout
- [ ] How it works: 3 Step Items on the Ink background
- [ ] Footer: 4 columns, legal line
- [ ] Set every section to Auto Layout with "Fill container" width
- [ ] Share the Figma link (view access: anyone with the link)

## 6. Submission

1. Create a GitHub repository named `nidaan-landing-page`.
2. Upload `index.html`, `README.md`, and Figma screenshots (`/screens` folder).
3. Add the Figma link in section 1 of this file.
4. Paste the repository link in the Google Sheet.

Optional: enable GitHub Pages (Settings → Pages → Deploy from branch `main`) to get a live link.
