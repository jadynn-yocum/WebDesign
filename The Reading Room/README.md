## Project 2 Reflection

### 1. What’s one HTML, CSS, or publishing skill you feel stronger in now?
I definitely feel a lot more comfortable using CSS Grid, Flexbox, and custom color variables (`:root`). Using `grid-template-columns: repeat` made it way easier to get the cards on the Discovery Hub and The Vault to adjust to different screen sizes automatically. I also figured out how to use `display: flex` with `margin-top: auto` on the Access Hub cards so the buttons always line up nicely at the bottom, even when one card has more text than the other.

### 2. How did it feel to navigate your own site? Is there anything that could make it more intuitive or enjoyable?
Clicking around between the Discovery Hub, The Vault, and the Access Hub feels pretty smooth thanks to the sticky top nav bar and the "Back to Discovery Hub" links at the bottom of the pages. One thing that would make it flow even better is connecting the pages a bit more—like adding a link inside the book matches on the home page that takes you straight to that book's breakdown in The Vault, or linking the Access Hub buttons to real library card sign-up pages and Libby.

### 3. Where did you struggle during the project: how did you address it (or plan to next time)?
Keeping the dark-forest "glass" aesthetic consistent across three separate HTML files—while still giving each page its own accent color—took some trial and error. At first, the blurred background glow orbs also caused annoying horizontal scrolling on smaller screens. I fixed that by adding `overflow-x: hidden` to the `body` and reusing the same `:root` color palette on every page. Next time, I'd put all the shared CSS into one external `styles.css` file so I don't have to copy and paste changes across three files.

### 4. If you had just one more week to work on this project, what would you add, change, or refine?
If I had another week, I'd move all the `<style>` code into a single external stylesheet to clean things up. I'd also add a few more hobby cards to the Discovery Hub (like Music, Art, or Sports) and throw in a quick filter button in The Vault so people can easily sort between audiobooks, graphic novels, and regular reads.

### 5. What are you most proud of? Did anything surprise you?
I'm really happy with the overall vibe of **The Reading Room**—especially the "Vibe Check" breakdowns in The Vault and the interactive click-to-reveal cards on the home page. It honestly surprised me how much the dark glass cards, soft background glow orbs, and casual copywriting changed the whole mood. Instead of feeling like a boring school reading list, it actually feels like a fun place to find something to read.
