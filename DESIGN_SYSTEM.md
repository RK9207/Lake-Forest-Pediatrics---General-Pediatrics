# Design system — General Pediatrics

## Visual personality

Use a warm, compact editorial layout that feels local and approachable. Give the strongest visual weight to the service, selected office, and primary action. Let one authentic care-team feature provide the emotional center of the page. Use generous space and a consistent type hierarchy so caregivers can scan between these points on a phone.

## Color, typography, and layout

Use the supplied brand palette below. Typography remains provisional because the brand fonts could not be verified. The brief specifies blue text and icon on the green mobile call button. That pairing has insufficient contrast at 1.23:1, so use white text and icon on green at 4.70:1 and keep the supplied blue for secondary actions on light surfaces.

| Role | Value | Use |
| --- | --- | --- |
| Canvas | `#FFFFFF` | Hero, services, and practical answers. |
| Primary text | `#172F38` | Headings, body copy, and text on light buttons. |
| Secondary text | `#475B61` | Helpful context, captions, and supporting labels. |
| Primary brand and action | `#1A8362` | Solid call buttons with white text and icon. |
| Action hover | `#155B53` | Hover and pressed backgrounds for solid call buttons. |
| Secondary brand and action | `#1B67B2` | Request Appointment, secondary controls, and underlined links on light surfaces. |
| Warm surface | `#FAF3EA` | One tinted care-team section. |
| Contact surface | `#DAF5FE` | Brand tint for the contact section, with a white GHL popup surface. |
| Supporting brand accent | `#5D3148` | Restrained emphasis for small labels or detail on light surfaces. |
| Form control border | `#688279` | Visible input and selector boundaries. |
| Divider | `#D4DED9` | Section rules between service or directory entries. |
| Error | `#A12838` | Error text on white or light surfaces. Pair color with a clear message. |

- **Typography** — Use Source Sans 3 as a draft base with a system sans-serif fallback. Use 36–40 px for the mobile H1 and 50–56 px on desktop. Use 26–34 px for H2s and at least 16 px for body, buttons, and inputs. Use body line height around 1.5 and aim for 55–65 characters per line in reading sections.
- **Grid and widths** — Use a single column below 768 px. Between 768 and 1,023 px, split content only when the service, CTAs, and form can keep their intended reading order. At 1,024 px and above, use a 12-column grid within a 1,120 px container. An optional 7/5 hero split gives the text first priority. Keep the form to roughly 480 px where space permits.
- **Spacing and details** — Use 20 px mobile and 32 px desktop side gutters. Start from an 8 px spacing scale, with 40–48 px between mobile sections and 64–80 px on desktop. Use restrained 8–12 px radii, subtle borders, and simple icons with visible labels.
- **Interaction** — Use visible keyboard focus, underlined text links, and touch controls at least 44 px high. Keep animation to short state transitions and respect reduced-motion preferences. Preserve the reading order and verify zoom, wrapping, and keyboard behavior on narrow screens.

## Visual storytelling system

| Moment | Composition and emphasis | Image role | Mobile direction |
| --- | --- | --- | --- |
| Hero | Lead with Lake Forest Pediatrics, general pediatric care, the selected office, and the primary call action. Include the appointment popup trigger and the Google Reviews badge once the rating and count are confirmed. | Use one approved office or team photo when it adds local trust and the page has distinct proof imagery. A text-led hero is suitable when the care-team photo is the strongest asset. | Present the service, office, and actions before any image. Show the office selector where a location is unknown. |
| Services | Use a short, text-led list with strong headings and practical benefits. Create a quieter passage after the hero. | Let the service names and benefits carry the section. | Stack entries with spacing or dividers so the most relevant services remain easy to find. |
| Care-team proof | Use a warm-tinted, contained editorial section with one image, a caption, and a brief proof point. | Use authentic team or provider photography to help families picture who they may meet. Verify the subject, office, and right to use the image. | Keep the photo, caption, and team context together. Use a concise text feature if proof photography is unavailable. |
| Google Reviews | Use a dedicated section for the confirmed rating, count, and selected reviews. Place **Read all our Google reviews** after the excerpts. | Keep the focus on review text and attribution. | Display up to three reviews at once on mobile and up to six on desktop. |
| Getting started | Shift to a lighter, text-led section. Use visible short answers for common barriers. | Keep the focus on practical information. | Let the questions scan quickly and keep the most consequential answers easy to find. |
| Contact | Make this the second visual peak. Put the selected office beside the call action and **Request Appointment**. Explain the next step above the embedded form inside its popup. | Give the contact actions and office details the available space. | Keep the popup usable at narrow widths, including with the keyboard open. Preserve readable error and success states. |
| Map and footer | Close with a responsive map, **Get Directions**, and a compact directory of all three offices. | Use the map to support navigation and keep addresses and directions available separately. | Stack offices consistently and keep the selected one identifiable in text. |

A headline-only scan should answer what the practice offers, where to reach it, who provides care, and how to request a visit or call. Use changes in spacing and background to distinguish the early relevance, care-team proof, and closing contact moments. Keep the services and practical answers quieter so the main actions remain easy to find.

## Components and assets

- **Header and office selector** — Use the supplied logo linked to the practice website. Use a sticky desktop header with balanced navigation, the phone CTA, and **Request Appointment**. On mobile, show the logo and brief’s **Book Appointment** button, which opens the same request popup. Label the selected office near the hero action and make switching available near contact.
- **Buttons and links** — Use one solid primary action per contact grouping and a clearly labeled secondary action. Keep the office, visible phone number, `tel:` link, and form updated together. Use consistent action labels in the hero and contact area.
- **Lists, cards, and reviews** — Favor a short list for services. Reserve elevated surfaces for the form or a single proof feature. Format an approved review as a brief quote with verified attribution. Avoid repeating the same card layout across sections.
- **FAQ** — Use plain-text questions or an accessible accordion with visible expanded states and keyboard support. Give the most important eligibility and scheduling details prominence above the form.
- **Form popup** — Use the brief’s GHL embed and preserve its supplied settings unless an integration change is necessary. Show the selected office above the form and provide a clear close action, keyboard focus containment, and focus restoration. Verify that labels, errors, and submission feedback are usable in the embed.
- **Office directory and map** — Keep all three offices visible with sourced addresses and directions. Use a responsive, lazy-loaded map and a **Get Directions** button with a location icon. Verify which office the supplied map depicts and obtain the remaining embeds before assigning maps by office.
- **Sticky CTA** — Use a mobile bottom call button with a phone icon and the active number. Account for safe areas and make sure the bar does not cover important content or overlap the appointment popup.
- **Imagery** — Prefer approved clinic-supplied photos. Use Google Business Profile photos only after checking permission and the location depicted. Use a roughly 4:3 crop for a hero image and 3:2 for editorial proof, with room around the subject for mobile cropping. Add alt text for meaningful images. Use generic lifestyle or AI imagery only with approval and only when it adds a clear editorial purpose. Use authentic imagery to represent the practice, its clinicians, and its offices.

Source for brand colors, navigation, reviews, contact form, map, and mobile requirements. [General Pediatrics project brief](%23Lake%20Forest%20Pediatrics%20-%20GENERAL%20PEDIATRICS%20PROJECT%20BRIEF.md)
