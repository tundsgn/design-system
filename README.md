# Design System — tundsgn

Multi-brand token architecture built in Figma, 
exported as JSON for cross-platform use.

## Token Architecture

### Brand (Primitive)
Raw values — colors, spacing, typography base.
129 variables.

### Alias (Semantic)
Maps Brand tokens to meaningful roles.
75 variables · 3 brand modes: Brand 1, Brand 2, Brand 3

### Mapped (Component)
Maps Alias tokens to Light/Dark themes.
85 variables · 2 modes: Light, Dark

### Responsive
Layout tokens across breakpoints.
42 variables · 3 modes: Desktop, Tablet, Mobile

## Switching Brands
Change the Alias layer → entire system updates.
No need to touch Brand or Mapped tokens.

## Files
- `Brand.json` — primitive tokens
- `Alias.json` — semantic tokens  
- `Mapped.json` — component tokens
- `Responsive.json` — layout tokens

## Tools
Figma Variables · Export/Import Variables plugin
