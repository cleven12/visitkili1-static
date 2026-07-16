Design a landing page for "VisitKili Adventures," a Tanzania-based safari and Kilimanjaro trekking company. Style: clean, professional, minimal — like a premium tour operator site (think Altezza Travel, Tanzania Specialist), NOT a generic travel-template look. Flat design only: no drop shadows, no glassmorphism, no blur effects. Separation comes from whitespace, 1px borders, and color, not depth effects.

COLORS (use as Tailwind theme colors, not defaults):
- vk-blue: #0284c7 (links, secondary accents)
- vk-orange: #E8720C (primary CTA buttons, highlights)
- vk-green: #1A3A2A (headers, footer background, dark text)
- vk-sand: #FFF8EE (warm off-white section background)
- White (#FFFFFF) alternating with vk-sand between sections for rhythm

TYPOGRAPHY: one clean modern sans-serif (Manrope or Plus Jakarta Sans via next/font, self-hosted, not Google Fonts CDN). Fluid type sizing with Tailwind's clamp-based text sizes — headings should scale smoothly between mobile and desktop, not jump at breakpoints.

STRUCTURE, top to bottom:
1. Thin top utility bar (vk-green bg): phone + email with icons on left, social icons (Facebook/Instagram/YouTube) on right. Hidden on mobile.
2. Main nav: logo left, flat text links (Kilimanjaro, Safaris, Zanzibar, Day Trips, Guides, About), orange "Get Free Trip Plan" button right. No mega-menu, no dropdown clutter — simple and confident.
3. Hero: centered, white background. Small orange eyebrow label ("Tanzania Safari & Trekking Specialists"), large fluid-sized headline ("Climb Kilimanjaro. See the Serengeti. Relax in Zanzibar."), subtext, two buttons (primary orange "Plan My Trip," outline "Browse Tours"). No hero background image — let a staggered image section below carry the visuals instead.
4. Staggered/offset photo showcase: a row of 4-5 images at different vertical offsets (alternating some raised, some lowered — asymmetric flowing arrangement, not a uniform grid), each a rounded rectangle, showing: a tourist summiting Kilimanjaro at sunrise, a safari jeep with wildlife in the Serengeti, a couple on a Zanzibar beach, hot air balloons over the plains, a close-up of Big Five wildlife. Use placeholder/stock-style images. Small caption label on each.
5. Trust bar: grayscale-until-hover logo row (TripAdvisor, Google, SafariBookings) on sand background, centered, generous spacing.
6. Featured tours: section heading with orange eyebrow ("Popular Right Now") + "Featured Tours". Fluid grid (auto-fit, not fixed 3-column breakpoints) of tour cards — image, category tag, title, days/difficulty stats row, price, "Details" button. 6 sample cards mixing Kilimanjaro treks and safaris.
7. "Why VisitKili" — 3-4 icon+text value props (local expertise, transparent pricing, small groups, safety) in a fluid grid, flat style, no cards/borders — just icon, heading, one line.
8. Testimonials: 2-3 review quotes in simple bordered cards, star rating, traveler name/country.
9. CTA banner: vk-green background, white text, "Ready to start planning?" + orange button.
10. Footer: vk-green background, 4 columns (brand+description, Explore links, Support links, Contact+social), bottom bar with copyright.

BEHAVIOR: mobile-first, fluid layout (CSS clamp/auto-fit over fixed breakpoints wherever possible), fast-loading (no heavy animation libraries), subtle scroll-reveal fade-up on sections is fine, but keep it lightweight. Use next/image for all images. This is a landing page only — no routing to other pages needed, just anchor links in nav.
