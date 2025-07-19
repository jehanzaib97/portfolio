
---

## 🎨 Customization Guide

| What to change | Where |
|----------------|-------|
| **Personal info** | `<title>`, `<h1>`, hero text, contact details |
| **Images** | Replace `<img>` src attributes |
| **Colors** | Edit CSS variables in `:root` |
| **Projects** | Duplicate `.project-card` blocks |
| **Timeline** | Add / remove `.timeline-item` entries |
| **Tech stack** | Tweak `.skills-list` & `.tech-stack` |
| **Social links** | Update `<a class="social-link">` hrefs |

---

## 🧪 Tech Stack (Internal)

- **Fonts**: Inter, Clash Display, Satoshi via Google Fonts  
- **Icons**: Inline SVG (feather-style)  
- **Particles**: CDN `particles.js@2.0.0`  
- **Scroll Snap**: Pure CSS (`scroll-snap-type: y mandatory`)  
- **Glassmorphism**: `backdrop-filter: blur(10px)` + `rgba()` borders  

---

## 📱 Responsive Breakpoints

| Width | Behavior |
|-------|----------|
| `> 1024 px` | Horizontal hero, side-by-side contact |
| `≤ 1024 px` | Stacked hero, timeline collapses to left |
| `≤ 768 px`  | Single-column project grid, nav labels hidden |

---

## 🛠️ Known Limitations

- Single-file architecture means all assets are inline or CDN.  
- No server-side contact form — current form uses `alert()` for demo.  
- Replace `alert` with fetch to your own endpoint for production.

---

## 📄 License

Released under the [MIT License](https://opensource.org/licenses/MIT).  
Use freely, credit appreciated.

---

Made with 💜 by Alex Chen – [alex@alexchen.dev](mailto:alex@alexchen.dev)