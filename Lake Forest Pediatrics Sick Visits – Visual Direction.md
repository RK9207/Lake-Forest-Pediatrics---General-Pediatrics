# Lake Forest Pediatrics Sick Visits – Visual Direction

Nov 26, 2026 · @Rohit Kumar

## 1. Visual direction

- Use a warm, compact healthcare layout.
- Make service, location, and the action legible immediately, then let the hours, visit explanation, and practice proof build confidence in that order.
- Give the experience a clear mobile reading sequence before adding desktop compositions.

## 2. Working colors

No verified brand palette or typography was supplied. Use these draft defaults and reconcile them with approved practice branding before launch. Preserve accessible contrast and the visual distinction between call and inquiry actions when adapting the palette.

| Role | Draft color | Use |
| --- | --- | --- |
| Canvas | `#FFFFFF` | Hero, visit explanation, FAQ, and form surfaces. |
| Primary text | `#182E39` | Headings and body copy. |
| Supporting text | `#475D68` | Captions, location context, and explanatory text. |
| Primary action | `#11655F` | Call buttons with white text and key text links. |
| Action hover | `#0B514D` | Hover and pressed states for the primary action. |
| Soft teal surface | `#EAF5F2` | Early hours band or restrained supporting highlights. |
| Contact surface | `#12343D` | Final contact area with white text and a light call button. |
| Divider | `#CEDDDC` | Subtle separators. Use `#667E85` for form control borders that need stronger definition. |
| Error | `#A12838` | Form errors on light surfaces. Include text to explain the error. |

### 2.1 Focus and accessibility

- Use visible keyboard focus wherever a control can be activated.
- Use a dark teal outline on light surfaces and a white outline on the dark contact surface, with an offset so the ring stands out from the control edge.
- Underline inline links and use text with any icon or color conveying necessary information.

## 3. Type, grid, and spacing

### 3.1 Typography

Use Source Sans 3 as a draft base, with a system sans-serif fallback. Use a single family to maintain a cohesive, approachable feel. Keep long text within roughly 65 characters per line.

| Element | Size | Notes |
| --- | --- | --- |
| H1 | Around 36–40 px on mobile and 52–56 px on desktop | Semibold |
| H2 | Around 26–36 px | — |
| Body copy | Around 17–18 px | At least 1.5 line height |

### 3.2 Width and grid

| Breakpoint | Layout |
| --- | --- |
| All widths | Keep content within 1,120 px. |
| Below 768 px | Single column. |
| 768 px and above | Allow a split hero and split contact area if the content reads comfortably. |
| Around 1,024 px and above | 12-column grid with a roughly 7/5 hero split that favors the text. Keep the CTA on the text side. |

### 3.3 Spacing

| Spacing | Mobile | Desktop |
| --- | --- | --- |
| Side gutters | 20 px | 32 px |
| Between major sections | About 40–48 px | About 64–80 px |

Use an 8 px spacing scale with tighter gaps for labels and related details.

### 3.4 Detail

- Use restrained 8–12 px corner radii and light dividers.
- Use simple icons for clearly labeled functions such as a call or directions.
- Keep motion to brief state changes and honor reduced-motion preferences.

## 4. Visual storytelling system

**Headline-only scan.** On a headline-only scan, the visitor should see:

1. A pediatric sick-visit offer
2. When to seek a visit
3. What the practice can do
4. Who they are contacting
5. How to call or send an inquiry

**Visual peaks.** Use one visual peak for first-screen relevance and a second for contact. Give the visit explanation and FAQ enough whitespace to support quick reading.

| Section | Composition and emphasis | Image role | Mobile treatment |
| --- | --- | --- | --- |
| Hero | Practice name, service headline, selected office, and primary call button lead. The supporting line sets a calm tone and points toward availability. | One authentic care-team or clinic image to establish trust. Use a quiet, text-led hero if suitable imagery is unavailable. | Service, office, and call action precede the image. Keep the image compact or omit it if it pushes availability too far down. |
| Availability | Full-width soft teal band with the key hours in three labeled entries. Visually distinguish same-day visits, the Sunday window, and the care line. | Text-led so the hours remain the visual focus. | Stack the three entries with short labels and a nearby call link. |
| Visit explanation | A contained editorial section with one benefit-led heading and a short explanation of evaluation and on-site testing. | Use a real exam-room or team image only when it adds context and is distinct from the hero image. | Keep the explanation first. Let the section remain text-led when the image adds little. |
| Practice proof | One contained proof moment with a caption, or a relevant, approved review. Keep the design quieter than the hero and contact area. | Use authentic practice, team, or office imagery to establish local credibility. Verify the person and location pictured. | Keep the photo and caption together and the proof immediately before contact. |
| Contact | Strong return to action on a dark teal background. Keep the phone and selected office prominent. Place the form on a light surface with readable spacing. | Use the space for contact information and form controls. | Place the office label and call action before the form. Keep focus and error messages visible if a sticky control is present. |
| FAQ and footer | Shift back to quieter surfaces. Use short questions, light dividers, and a compact directory. | Use directions links as the default location aid. Consider a map only when it adds useful location context. | Stack questions and office entries. Keep the selected office identifiable and all three offices visible. |

## 5. Components

| Component | Guidance |
| --- | --- |
| Header | Use the approved logo or practice name and a compact contact action when space allows. Keep the service and selected office prominent in the hero. |
| CTA | Use a solid teal button on light surfaces and a light button with dark text on the contact surface. Use a secondary text action for the form jump. Give controls at least a 44 px touch target. Keep the displayed number and `tel:` link in sync with the selected office. |
| Cards and reviews | Reserve individual surfaces for content that needs separation, especially the form. Use lines, spacing, and type for hours and benefits. Present any approved review as a short quote with verified attribution. |
| FAQ | Prefer visible short answers or a compact accessible accordion if length warrants it. Use descriptive question labels, keyboard-operable controls, and an expanded state users can identify. Keep the primary availability information above the FAQ. |
| Form | Use one column, persistent field labels, visible required indicators, and accessible errors close to the affected fields. Keep the selected office next to the form and submission status in the same area. Use practice-approved fields and routing. |
| Map and locations | Default to a lightweight office directory with verified direction links. If a map adds value, keep the office details and actions available in text and avoid delaying initial content for the embed. |
| Sticky CTA | Optional on mobile if the hero call action scrolls out of view. Use one call action for the active office or a verified fallback. Check the safe area and avoid covering form controls, feedback, or footer content. |

## 6. Imagery and assets

### 6.1 Sources

- Prefer approved photos supplied by the clinic.
- Google Business Profile photos can serve as reference or be used when the practice confirms usage rights and whether they show the correct office.

### 6.2 Style

- Favor natural light, approachable expressions, and relevant clinical or neighborhood context.

### 6.3 Crops and alt text

| Image | Crop |
| --- | --- |
| Hero | Roughly 4:3, with space around subjects |
| Proof (optional) | 3:2 |

Check narrower crops before launch, keep important details clear, and provide alt text where the image conveys useful information.

### 6.4 Lifestyle and AI imagery

- If lifestyle imagery helps communicate reassurance, use a single generic family image where it contributes to the story.
- Use AI imagery only for generic illustrative scenes with approval.
- Represent the actual clinic, care team, patients, and local offices with verified authentic assets.

### 6.5 Keep free of decorative photography

- The availability band
- The FAQ
- The form
