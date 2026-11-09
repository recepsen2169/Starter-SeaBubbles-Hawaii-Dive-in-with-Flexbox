# SeaBubbles hawaii - Flexbox Project Reflection 

### 1. Effect of the Layout Breakpoints
The layout adapts responsively at three critical CSS-pixel widths to optimize the course cards layout display:
**Large Breakpoint (992px): ** Changes the flex-basis properties to 20% to neatly arrange all four course cards horizontally in a sleek, full single-row desktop layout.
**Medium Breakpoint (768px): ** Drops the flex-basis properties down to 48%, wrapping the elements gracefully into a clean 2-column stacked grid layout.
**Small Breakpoint (576px): ** Reverts the cards back to a full 100% basis width so they stack vertically on mobile phone displays for optimal readable content layout.

### 2. Flex Container Rules Observed
**justify-content:** Used to distribute empty spaces evenly across the main inline line rows, keeping the gap separation clean and aligned across varied viewport margins.
**align-items:** Keeps column card groupings structurally stretching and sitting identically, ensuring button layout points don't look broken across.