# Aurora After Wedding Website Master V2

This is the reusable, design-neutral product backbone for Aurora After's wedding website templates.

## Product architecture

### Core sections — always included
1. Hero / Cover
2. Invitation
3. Countdown
4. Our Story
5. Wedding Details
6. Wedding-Day Timeline
7. Venue + Map
8. RSVP
9. Contact
10. Closing

### Optional modules — buyer can delete if not needed
- Weekend Events
- Travel & Stay
- Transportation / Shuttle
- Dress Code
- Wedding Party
- Things To Do
- Food & Bar
- Gallery
- Registry
- FAQ

## Why this structure
The master is deliberately modular. A finished aesthetic should be a visual "skin" placed over the same bones. Buyers should not need to use every module.

The GitHub demo includes an internal **Master controls** button that toggles optional modules on/off. This simulates what the buyer would do by deleting or keeping sections inside Canva.

The customer-facing Canva version should NOT show these controls. It should simply include all optional modules, clearly grouped so the buyer can delete the ones that do not apply.

## Navigation
Desktop: core links + a **More** dropdown containing optional modules.
Mobile: compact navigation with the More dropdown and RSVP.

## Next production step
After the architecture is approved, recreate this master in Canva as the neutral master template. Freeze the section order, spacing rules, responsive considerations, button system, and module library. Duplicate that master for each new visual trend/aesthetic.

## GitHub Pages
Upload `index.html` to the repository root, then use:
Settings → Pages → Deploy from branch → main → /(root)
