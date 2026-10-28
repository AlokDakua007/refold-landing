# Refold AI — Landing page (Figma "Desktop - 2" → HTML/CSS)

Static HTML/CSS build of the **Desktop - 2** frame (1440 px artboard) from the Refold Figma file.

```
index.html   – page markup, one block per Figma section
styles.css   – design tokens (colours, gradients, type) + component styles
assets/      – SVG/WebP assets exported from Figma
fonts/       – self-hosted DM Sans, DM Mono, PT Serif (OFL)
```

Open `index.html` directly in a browser — no build step.

## Components (map to Figma components)
| Class | Figma |
|---|---|
| `.btn--primary` + `.arrow-box` | RRBtn (Default / Variant5) |
| `.btn--outline` | WATCH AGENTS / VIEW DOCUMENTATION |
| `.btn--white` | RRBtn Variant3 |
| `.btn--nav` | bookdemo |
| `.nav__link` | NAV_btn |
| `.label-head` (`--dark`, `--blue`) | Labelhead1 + LOGO3 |
| `.bars` | HOMEGradient / Rectangle 42 stacks |
| `.cols` | Component 21 / 22 |
| `.logo-cell` + `.tag` | Trust logo frames + "CASE STUDY" tag |
| `.pain-card`, `.team`, `.deploy-card` | Problem / Teams / Deployment cards |
| `.accordion` / `.acc-item` | "(closed) barline afterdelay" (auto-advances every 6 s) |

Verified against the Figma export: every section's top offset and height match the frame (total 7151 px).
