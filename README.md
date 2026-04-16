# ROUTES Project Showcase Website

**Redesigning Optimal Urban Transportation for Equitable School Access**

A professional capstone showcase website for the NYU CUSP ROUTES project, presenting school bus route optimization analysis with a focus on equity and efficiency.

---

## Website Structure

```
routes-website/
├── index.html          # Main showcase website (single-page)
├── README.md          # This file
└── imgs/               # Image assets
    ├── hero_bus.jpg                    # Generated: Hero image (NYC school bus)
    ├── diversity_scene.jpg             # Generated: Children at bus stop scene
    ├── nyc_transport.jpg              # Generated: NYC transport ambiance
    ├── route_K612_before_map.png      # Local: Original K612 route map
    ├── route_K612_after_map.png       # Local: Optimized K612 route map
    ├── route_L657_before_map.png      # Local: Original L657 route map
    └── route_L657_after_map.png       # Local: Optimized L657 route map
```

---

## Content Sources

### Local Materials (from Capstone folder)

All route maps and data tables were sourced from the original project materials at `C:\Users\10418\Downloads\Capstone`:

| File | Description | Usage in Website |
|------|-------------|------------------|
| `route_K612_before_map.png` | K612 original route visualization | Route comparison - before state |
| `route_K612_after_map.png` | K612 optimized route with segment reassignment | Route comparison - after state |
| `route_L657_before_map.png` | L657 original route visualization | Route comparison - before state |
| `route_L657_after_map.png` | L657 optimized route (timing changes only) | Route comparison - after state |
| `two_route_case_summary.csv` | Summary of both routes with intervention results | Key metrics extraction |
| `two_route_before_after_comparison.csv` | Detailed before/after metrics | Quantitative data |
| `route_A_intervention_plan.csv` | L657 intervention strategy details | Intervention caption |
| `route_B_intervention_plan.csv` | K612 intervention strategy details | Intervention caption |

### Generated Images

The following images were AI-generated specifically for this website to provide high-quality visual ambiance:

1. **hero_bus.jpg** - Photorealistic yellow school bus on NYC residential street
2. **diversity_scene.jpg** - Diverse children at school bus stop, morning light
3. **nyc_transport.jpg** - Modern NYC street scene with transportation context

All generated images comply with:
- No text, logos, or watermarks
- No copyright-risk elements
- Academic showcase appropriate quality
- Photorealistic style matching project theme

---

## Design System

### Color Palette

| Color | Hex | Usage |
|-------|-----|-------|
| NYU Violet | `#57068c` | Primary brand color |
| Deep Violet | `#330662` | Dark accents, backgrounds |
| Tandon Teal | `#00A99D` | Accent for improvements/positive changes |
| White | `#ffffff` | Primary background |
| Light | `#f8f7fc` | Section backgrounds |
| Text Dark | `#1a1a2e` | Primary text |
| Text Medium | `#4a4a5a` | Secondary text |
| Border Light | `#e8e6f0` | Subtle borders |

### Typography

- **Headings**: Inter (600-700 weight), clean modern sans-serif
- **Body**: Inter (400-500 weight), highly readable
- **Research Question**: Source Serif 4 for emphasis and academic feel

---

## Website Sections

1. **Hero** - Project title, tagline, key statistics
2. **Overview** - Project explanation and approach
3. **Research Question** - Core research framing
4. **Why This Matters** - Equity and burden considerations
5. **Methodology** - Four-step analytical workflow
6. **Key Visual Findings** - Before/after route comparisons with metrics
7. **Recommendations** - Operational implications
8. **Deliverables** - Project outputs
9. **Team** - Project members and sponsors
10. **Footer** - Standard closing with links

---

## Key Data Points

### Route K612 (Shema Kolainu Hear Our Voices School)

| Metric | Before | After | Change |
|--------|--------|-------|--------|
| AM Burden | 195 min | 146 min | -25% |
| PM Burden | 660 min | 561 min | -15% |
| Run Span | 1,305 min | 940 min | -28% |
| Intervention | — | Segment Reassignment + Time Window Shift | — |

### Route L657 (Fusion Academy Brooklyn)

| Metric | Before | After | Change |
|--------|--------|-------|--------|
| AM Burden | 210 min | 147 min | -30% |
| Run Span | 570 min | 456 min | -20% |
| Intervention | — | Stop Merge + Pickup Window Tightening | — |

---

## Data Handling Notes

- All quantitative data sourced directly from project CSV tables
- No sensitive original data (route-level details, student information) exposed
- Equity vulnerability notes preserved from original analysis
- All intervention descriptions match original intervention_plan.csv files

---

## Browser Compatibility

- Modern browsers (Chrome, Firefox, Safari, Edge)
- Responsive design for desktop, tablet, and mobile
- Scroll-based animations with graceful degradation

---

## Deployment

This is a static website requiring no server-side dependencies. Simply open `index.html` in any modern browser, or deploy the entire `routes-website` folder to any static hosting service.

---

## Credits

- **Project**: ROUTES — Redesigning Optimal Urban Transportation for Equitable School Access
- **Institution**: NYU Center for Urban Science + Progress (CUSP)
- **Sponsor**: NYCSBUS
- **Year**: 2026
