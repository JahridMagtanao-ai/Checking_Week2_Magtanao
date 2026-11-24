# HANDOFF.md - Pickleball Fun

**Student:** [Your Full Name]
**Activity:** Activity 6
**Checkpoint:** Week 1
**Project Title:** Pickleball Fun: A Simple Website for Pickleball Beginners

---

## UX Project Proposal

### 1. User Problem
Some people do not know what pickleball is, how to play it, or what equipment they need.

### 2. Target Audience
- Students
- Beginners
- People interested in sports

### 3. Website Pages
1. **Home** - Welcome page with a pickleball picture.
2. **About** - Short introduction to pickleball.
3. **Rules** - Basic rules of the game.
4. **Gallery** - Pictures of pickleball.
5. **Ask Us** - Ask a question or send a request.

### 4. Design Theme
- **Colors:** Green, white, and yellow.
- **Style:** Simple, clean, and sporty.
- **Font:** Arial.

### 5. Website Goal
To help beginners understand pickleball and learn the basic things they need to start playing.

### 6. Interface Goals
- Easy to navigate: all five pages reachable from the top menu.
- Clear, readable text with strong contrast (dark text on white, white text on green).
- Short sections so beginners are not overwhelmed.
- Built with basic HTML and CSS only.

---

## Design Tokens (declared in `css/style.css` `:root`)

| Group | Tokens |
|---|---|
| Color | `--color-primary` #1b8a4b (green), `--color-bg` #ffffff (white), `--color-accent` #f5d90a (yellow) |
| Typography | `--font-family` Arial, size scale `--fs-sm` to `--fs-2xl` |
| Layout | `--container-max` 1000px, spacing scale `--space-1` to `--space-6` |

## Workspace Structure

```
Activity6_Lastname/
├── index.html      (Home)
├── about.html
├── rules.html
├── gallery.html
├── ask.html
├── HANDOFF.md
├── css/
│   └── style.css
└── assets/
    └── images/
```

## Roadmap
- **Week 2:** Header/navigation, Home, and About sections.
- **Week 3:** Rules, Gallery, Ask Us, footer, and final polish.

---

## Navigation Design

The site uses one sticky green navigation bar at the top, with the site name on the left and five links on the right. On phones the logo stacks above the links. Each link opens its own page, and the same menu appears on every page.

| Nav item | Links to | Purpose / why it is there |
|---|---|---|
| **Pickleball Fun** (logo) | `index.html` | Shows the site name and always returns the visitor to the top, as users expect. |
| **Home** | `index.html` | Welcome page with a pickleball picture. Gives first-time visitors a quick idea of the site. |
| **About** | `about.html` | Short introduction. Answers the beginner's first question: "What is pickleball?" |
| **Rules** | `rules.html` | Basic rules and equipment. Teaches beginners how to start playing. This is the main goal of the site. |
| **Gallery** | `gallery.html` | Pictures of pickleball. Makes the sport easy to picture. |
| **Ask Us** | `ask.html` | A form to ask a question or make a request (email opens with the message filled in). Yellow button style so it stands out as the last action. |

**Navigation UX decisions**
- The order follows a beginner's journey: welcome, learn what it is, learn how to play, see it, get in touch.
- Only five items, so the menu is never overwhelming.
- The current page gets a yellow underline, and hovering turns links yellow, so visitors always see where they are.
- Strong contrast (white on green) and visible keyboard focus outlines for accessibility.
