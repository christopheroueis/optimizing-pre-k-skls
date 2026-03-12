# A Day in the Life — Principal's Edition

Single new file `story.html` that delivers a cinematic 5-scene animated storybook narrating how a preschool principal uses the ClassroomIQ optimization tool.

## Proposed Changes

### [NEW] [story.html](file:///Users/macintoshhd/Desktop/90755-B%20-%20Optimization/opt-video/story.html)

Single self-contained HTML file (~2000 lines), no build step, containing:

| Aspect | Details |
|---|---|
| **Fonts** | Google Fonts `@import` — Playfair Display + Inter |
| **Color palette** | Warm amber `#d97706`, deep navy `#1e293b`, soft cream `#fef3c7`, accent coral `#f97316` |
| **Navigation** | Arrow keys, on-screen ◀▶ buttons, clickable progress dots. 800ms horizontal `translateX` transitions |
| **Backgrounds** | Full-bleed CSS gradients/SVGs per scene (sunrise, school, autumn leaves, winter frost, summer confetti) |
| **Character images** | [./nate.jpg](file:///Users/macintoshhd/Desktop/90755-B%20-%20Optimization/opt-video/nate.jpg), [./chris.jpg](file:///Users/macintoshhd/Desktop/90755-B%20-%20Optimization/opt-video/chris.jpg), [./rahul.jpg](file:///Users/macintoshhd/Desktop/90755-B%20-%20Optimization/opt-video/rahul.jpg), [./samuel.jpg](file:///Users/macintoshhd/Desktop/90755-B%20-%20Optimization/opt-video/samuel.jpg) — rounded frames, drop-shadows, floating bob animation |
| **Scene 1** | Morning sunrise gradient, animated title sequence, notification stack, speech bubble, glowing laptop CTA |
| **Scene 2** | [index.html](file:///Users/macintoshhd/Desktop/90755-B%20-%20Optimization/opt-video/index.html) in iframe inside CSS laptop mockup, tooltip overlays on 3s auto-timer, para character cards with cycling speech bubbles |
| **Scene 3** | Falling-leaves CSS particles, calendar flip, alert notification, para reactions, enrollment counter animation, constraint check readout |
| **Scene 4** | Frost/snow CSS effect, phone buzz, two interactive option cards (A/B), resolution animation on click |
| **Scene 5** | Confetti CSS particles, animated stat counters, group celebration layout, credits |
| **Particles** | CSS `@keyframes` for falling leaves (Scene 3), snow (Scene 4), confetti (Scene 5), light rays (Scene 1) |

## Verification Plan

### Browser Visual QA

1. Open `story.html` in browser via the browser tool
2. Walk through all 5 scenes verifying: transitions, animations, character images loading, iframe embed, interactive elements

> [!NOTE]
> No automated tests — this is a standalone visual presentation file. Verification is purely visual.
