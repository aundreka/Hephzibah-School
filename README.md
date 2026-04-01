# Hephzibah School Website

A responsive single-page site for Hephzibah School (Secondary), a DepEd-recognized institution in Silang, Cavite. The landing page highlights the school's mission, programs, facilities, admissions CTA, and contact channels, all wrapped in a "Play + Learn" story that mirrors the phrase "Are You Ready To Play?" The layout leans on Tailwind CSS via CDN and ambient micro-interactions to keep the message lively.

## Built With
- Plain HTML5 and semantic sections for accessibility and SEO.
- Tailwind CSS (via CDN) for layout, typography, gradients, and responsive grids.
- Google Fonts (Poppins + Playfair Display) and Font Awesome for typography and icons.
- Embedded Google Maps, Messenger deep-links, and CTA anchors for quick contact or enrollment.

## Hero & Story Sections
- Hero with gradient background, stat badges, CTA buttons (Enroll + Explore Activities), and a floating photo of students.
- Animated stat highlights (established date, academic levels, generation families, sports facilities) that frame trust.
- About block with campus imagery, mission statement, trust-building badges, transportation guide, and social links.

## Programs, Activities, Admissions & Contact
- Program cards listing the four academic levels (Pre-School through Senior High) with accreditive highlights.
- Activity grid covering sports, arts, tech, and fun learning-based clubs plus testimonials/awards that signal culture.
- Admissions timeline and quick contact form that funnels responses into Facebook Messenger.
- Contact panel with phone, email, hours, and messenger buttons plus floating Messenger FAB and click-to-call links.

## Assets & Media
- `logo.jpg`, `campus.jpg`, `students.jpg` are used for branding, campus story, and hero imagery.
- Background gradients, SVG wave, and CSS animations create motion without JavaScript dependencies beyond Light DOM behavior.

## Customization Tips
1. Update the contact numbers, email, schedule, or address if anything changes in `index.html` near the Contact/Office Hours sections (#contact, footer). Always keep the `tel:` and `mailto:` links in sync.
2. Replace the Messenger links/phone CTA with other CRM targets by editing the `href` attributes under the hero CTA buttons, footer, and FAB.
3. Swap images by replacing the files in the repo and keeping the same filenames, or adjust the `src` attributes throughout `index.html`.
4. Adjust copy (mission, stats, CTA promises) directly inside `index.html` text nodes; the file is purely static.

## Deployment
Any static host (GitHub Pages, Netlify, Vercel, S3, etc.) works. Simply upload `index.html`, `logo.jpg`, `campus.jpg`, and `students.jpg`. Prefer serving over HTTPS so Messenger deeplinks and Google Maps render properly.

## Next Steps
1. Run through the contact form to ensure Messenger linking still works from your hosting environment.
2. Consider adding analytics or a backend form if you want to capture inquiries without leaving the page.
