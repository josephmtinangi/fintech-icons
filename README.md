# Tanzania Fintech Icons — Brand Edition
**61 brand-referenced single-color line SVG icons**

## Brand References
| Icon | Brand Inspiration |
|---|---|
| M-Pesa | Vodacom speech bubble with bold "M" letterform |
| Tigo Pesa | Millicom diagonal slash through bold "T" |
| Airtel Money | Airtel "Wave" — open spiral lowercase "a" |
| HaloPesa | Halotel "H" with signal arc halo above |
| TTCL Pesa | TTCL broadcast tower mast |
| AzamPesa | Azam chevron peak "A" (Azam = great) |
| CRDB Bank | Three horizontal bars (CRDB bar motif) |
| NMB Bank | Bold "N" with diamond accent |
| DTB | Diamond Trust diamond mark |
| Stanbic | Standard Bank rising sun arcs |
| TRA | Scales of justice |
| Zantel | "Z" lightning bolt |
| TRC Tickets | Train/railway ticket |
| LUKU | Padlock with token chip (prepaid meter) |
| DAWASCO Water | Water droplet with ripple |
| TANESCO Electricity | Lightning bolt |

## Design System
- **ViewBox**: 48×48px
- **Style**: Stroke-only line icons (no fills except `fill="currentColor"` for accent dots)
- **Color**: Single color via `currentColor` — one CSS property changes everything
- **Stroke**: width 2, linecap round, linejoin round

## Usage
```css
.icon { color: #CC1111; width: 28px; height: 28px; }
```
```html
<img src="mobile-money/mpesa.svg" class="icon"/>
```
```jsx
// React with inline SVG for full color control
import MpesaIcon from './mobile-money/mpesa.svg?react';
<MpesaIcon className="icon" />
```

## Categories
`mobile-money` · `banks` · `money-transfer` · `payments` · `banking` · `telecom` · `government` · `investments` · `utilities` · `insurance` · `transport` · `crypto` · `identity` · `social`
