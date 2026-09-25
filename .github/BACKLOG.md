# Backlog

## Done

### Responsive layout: keep content centered in smaller browser windows
**Problem:** When the browser wasn't full screen, the layout looked off.
- The nav and hero header had their own `5vw` side padding, but the main content was a centered 900px column. So the header (name, avatar, links) and the nav didn't line up with the sections below, and the gap changed as the window was resized.
- On phone widths (~380px) the nav didn't fit. The brand wrapped onto two lines and the "Education" link was cut off, which caused a horizontal scroll.

**Acceptance criteria**
- [x] Nav, hero, content and footer left edges line up at 1440 / 1000 / 700 / 380px
- [x] No horizontal page scroll at 380px
- [x] On phones the nav stacks (brand above links) and stays usable
- [x] Project cards and screenshot strips use tighter padding on phones
